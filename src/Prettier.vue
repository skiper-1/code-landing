<script setup>
import { CodeBracketSquareIcon } from '@heroicons/vue/24/solid';
import { GlobeAltIcon } from '@heroicons/vue/24/solid';
import { CodeBracketIcon } from '@heroicons/vue/24/solid';
</script>

<template>
  <header class="container mx-auto my-4">
    <div class="container flex items-center justify-between gap-10">
      <a href="#" class="flex items-center gap-2">
        <CodeBracketSquareIcon class="size-20 text-indigo-500 -rotate-10" />
        <span class="text-3xl font-bold">Code Editor</span>
      </a>
      <nav class="grow">
        <ul class="flex items-center gap-10">
          <li class="mr-auto">
            <a href="#" class="font-bold hover:text-indigo-500">Library</a>
          </li>
          <li>
            <a href="#" class="font-bold hover:text-indigo-500">Log In</a>
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
    </div>
  </header>

  <main>
    <section class="flex flex-col py-16 gap-y-12 container mx-auto">
      <div>
        <h1 class="text-center text-5xl font-bold">Prettier</h1>
        <p class="text-center">
          Automatically format your code to ensure style across your project.
        </p>
      </div>
      <div class="container mx-auto grid grid-cols-3 gap-x-8">
        <div class="col-span-1 flex flex-col gap-y-4">
          <div class="flex justify-between items-center gap-x-4">
            <h3 class="font-semibold text-lg">Lessons</h3>
            <div class="flex">
              <a href="#" target="_blank" class="hover:text-indigo-500"
                ><GlobeAltIcon class="size-8"
              /></a>
              <a href="#" taget="_blank" class="hover:text-indigo-500"
                ><CodeBracketIcon class="size-8"
              /></a>
            </div>
          </div>
          <ul>
            <li>
              <a
                href="#"
                class="flex justify-between bg-indigo-50 rounded text-indigo-500 w-full p-3 gap-4"
                ><span class="truncate">1. Getting started with Prettier </span>
                <span>5:30</span>
              </a>
            </li>
            <li class="flex gap-5">
              <a
                href="#"
                class="flex justify-between w-full p-3 gap-4 hover:bg-gray-100 rounded"
                ><span class="truncate">2. Advanced GitLens Features </span>
                <span>6:30</span>
              </a>
            </li>
            <li class="flex gap-5">
              <a
                href="#"
                class="flex justify-between w-full p-3 gap-4 hover:bg-gray-100 rounded"
                ><span class="truncate"> 3. Debugging with ESLint </span>
                <span>7:30</span>
              </a>
            </li>
          </ul>
        </div>
        <div class="col-span-2">
          <iframe
            class="rounded-lg aspect-video w-full"
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
  <footer class="contaner bg-indigo-900 text-white font-extralight pt-10 px-20">
    <div class="flex items-center gap-16">
      <div class="w-1/2 flex flex-col gap-5">
        <a href="#" class="flex items-center gap-2">
          <CodeBracketSquareIcon class="size-12 text-white -rotate-10" />
          <span class="text-xl font-bold">Code Editor</span>
        </a>
        <p class="max-w-screen-sm">
          Unlock your coding potential with tailored settings, shortcuts, and
          expert tutorials.
        </p>
      </div>
      <div class="flex justify-evenly items-center gap-6 w-1/2">
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
    <div class="text-center mt-10 pb-2">
      &copy; 2025 Code Editor. All right reserved.
    </div>
  </footer>
</template>
