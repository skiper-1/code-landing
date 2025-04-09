<script setup>
import {
  CodeBracketSquareIcon,
  Bars3Icon,
  XMarkIcon,
  GlobeAltIcon,
  CodeBracketIcon,
} from '@heroicons/vue/24/solid';
</script>

<template>
  <header
    class="fixed top-0 inset-x-0 sm:static z-10 border-b-4 border-gray-300 bg-indigo-50 dark:bg-gray-900 dark:border-gray-700"
  >
    <div class="container flex items-center justify-between gap-10">
      <a href="#" class="flex items-center gap-1 sm:gap-2">
        <CodeBracketSquareIcon
          class="size-10 sm:size-12 text-indigo-500 -rotate-10"
        />
        <span class="text-xl sm:text-3xl font-bold dark:text-indigo-50"
          >Code Editor</span
        >
      </a>
      <nav class="grow hidden sm:block">
        <ul class="flex items-center gap-10">
          <li class="mr-auto">
            <a
              href="#"
              class="font-bold hover:text-indigo-500 dark:text-indigo-100"
              >Library</a
            >
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-indigo-500 dark:text-indigo-100"
              >Log In</a
            >
          </li>
          <li>
            <a
              href="#"
              class="p-3 font-bold rounded-lg bg-indigo-500 text-indigo-100 hover:bg-indigo-600"
              >Sign Up</a
            >
          </li>
        </ul>
      </nav>
      <div class="flex sm:hidden">
        <nav
          id="nav"
          class="absolute inset-x-0 bg-white border-b-4 border-gray-300 rounded-b-xl sm:border-0 top-full hidden target:block peer dark:bg-gray-900 dark:border-gray-700"
        >
          <ul class="flex flex-col items-center gap-2 px-3 py-3">
            <li class="w-full">
              <a
                href="#nav"
                class="inline-block w-full p-2 text-center rounded hover:bg-gray-100 dark:text-white dark:hover:bg-gray-600"
                >Library</a
              >
            </li>
            <li class="w-full">
              <a
                href="#"
                class="inline-block w-full p-2 text-center rounded hover:bg-gray-100 dark:text-white dark:hover:bg-gray-600"
                >Log In</a
              >
            </li>
            <li class="w-full">
              <a
                href="#"
                class="inline-block w-full py-2 px-3 text-center rounded bg-indigo-500 text-white hover:bg-indigo-700"
                >Sign Up</a
              >
            </li>
          </ul>
        </nav>
        <a
          href="#nav"
          class="hover:bg-gray-100 p-2 rounded-md peer-target:hidden dark:bg-gray-500 dark:hover:bg-gray-400"
        >
          <Bars3Icon class="size-10 block sm:hidden" />
        </a>
        <a
          href="#"
          class="hidden hover:bg-gray-100 p-2 rounded-md peer-target:block dark:hover:bg-gray-400 dark:bg-gray-500"
        >
          <XMarkIcon class="size-10" />
        </a>
      </div>
    </div>
  </header>
  <main>
    <section
      class="container flex flex-col pt-24 pb-6 sm:py-16 sm:gap-y-12 gap-y-8 dark:bg-gray-800 dark:text-white"
    >
      <div>
        <h1 class="text-center text-5xl font-bold">Prettier</h1>
        <p class="text-center">
          Automatically format your code to ensure style across your project.
        </p>
      </div>
      <div class="grid sm:grid-cols-5 grid-cols-1 sm:px-10">
        <div class="col-span-2 flex flex-col gap-y-4 px-4">
          <div class="flex justify-between items-center gap-x-4">
            <h3 class="font-semibold text-lg">Lessons</h3>
            <div class="flex">
              <a href="#" target="_blank" class="hover:text-indigo-500"
                ><GlobeAltIcon class="sm:size-8 size-6"
              /></a>
              <a href="#" taget="_blank" class="hover:text-indigo-500"
                ><CodeBracketIcon class="sm:size-8 size-6"
              /></a>
            </div>
          </div>
          <ul class="flex flex-col gap-2">
            <li>
              <a
                href="#"
                class="flex justify-between bg-indigo-50 rounded text-indigo-500 w-full p-3 gap-4 dark:bg-gray-700"
                ><span class="truncate">1. Getting started with Prettier </span>
                <span>5:30</span>
              </a>
            </li>
            <li class="flex gap-5">
              <a
                href="#"
                class="flex justify-between w-full p-3 gap-4 hover:bg-gray-100 rounded dark:hover:bg-gray-700"
                ><span class="truncate">2. Advanced GitLens Features </span>
                <span>6:30</span>
              </a>
            </li>
            <li class="flex gap-5">
              <a
                href="#"
                class="flex justify-between w-full p-3 gap-4 hover:bg-gray-100 rounded dark:hover:bg-gray-700"
                ><span class="truncate"> 3. Debugging with ESLint </span>
                <span>7:30</span>
              </a>
            </li>
          </ul>
        </div>
        <div class="col-span-3 px-4 sm:px-0">
          <iframe
            class="rounded-lg aspect-video w-full h-fit"
            width="886"
            height="498"
            src="https://www.youtube.com/embed/Zvd_iyYWF1E?list=PL-FhWbGlJPfad98AQLf-VP_vn_GRJR58T"
            title="VS Code | Минималистичная настройка 2025 (1/11) - Цветовая тема и интерфейс"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin"
            allowfullscreen
          ></iframe>
          <article class="prose">
            <header>
              <h3 class="pt-5 pb-3 text-lg font-bold">
                Getting started with prettier
              </h3>
              <p>
                Prettier is an opinionated code formatter that automatically
                formats your code for consistency and readability. It supports
                many languages like JavaScript, TypeScript, HTML, CSS, and more.
                With Prettier, you don’t need to worry about style debates or
                messy code. Just save your file, and it formats everything for
                you. It's a must-have tool for clean and professional codebases.
              </p>
            </header>
          </article>
        </div>
      </div>
    </section>
  </main>
  <footer
    class="container bg-indigo-900 text-white font-extralight py-2 sm:pt-10 sm:px-4 dark:bg-gray-900"
  >
    <div class="flex items-center flex-col sm:flex-row sm:gap-8 gap-6">
      <div class="sm:w-1/2 p-2 flex flex-col gap-5">
        <a href="#" class="flex items-center gap-2">
          <CodeBracketSquareIcon class="size-12 text-white -rotate-10" />
          <span class="text-xl font-bold">Code Editor</span>
        </a>
        <p class="sm:max-w-screen-sm">
          Unlock your coding potential with tailored settings, shortcuts, and
          expert tutorials.
        </p>
      </div>
      <div class="flex sm:justify-evenly items-center gap-6 sm:w-1/2">
        <div class="flex flex-col gap-5">
          <h2 class="font-medium">Popular playlists</h2>
          <ul class="flex flex-col gap-2">
            <li class="hover:text-indigo-500"><a href="#"> Prettier </a></li>
            <li class="hover:text-indigo-500"><a href="#"> GitLens </a></li>
            <li class="hover:text-indigo-500">
              <a href="#"> Live Share </a>
            </li>
          </ul>
        </div>
        <div class="flex flex-col gap-5">
          <h2 class="font-medium">Configurations</h2>
          <ul class="flex flex-col gap-2">
            <li class="hover:text-indigo-500"><a href="#"> Settings </a></li>
            <li class="hover:text-indigo-500"><a href="#"> Keybinding </a></li>
            <li class="hover:text-indigo-500"><a href="#"> Snippets </a></li>
          </ul>
        </div>
        <div class="flex flex-col items-center gap-5">
          <h2 class="font-medium">Social</h2>
          <ul class="flex flex-col gap-2">
            <li class="hover:text-indigo-500">
              <a href="#">YouTube</a>
            </li>
            <li class="hover:text-indigo-500">
              <a href="#">Telegram</a>
            </li>
            <li class="hover:text-indigo-500">
              <a>GitHub</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="text-center mt-10">
      &copy; 2025 Code Editor. All right reserved.
    </div>
  </footer>
</template>
