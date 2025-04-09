<script setup>
import {
  CodeBracketSquareIcon,
  Bars3Icon,
  XMarkIcon,
  Cog6ToothIcon,
  FireIcon,
  PuzzlePieceIcon,
  PaperAirplaneIcon,
} from '@heroicons/vue/24/solid';
</script>

<template>
  <header
    class="flex justify-center p-2 sm:py-4 fixed top-0 inset-x-0 sm:static z-10 border-b sm:border-0 bg-white dark:bg-gray-900"
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
          class="absolute inset-x-0 bg-white border-b rounded-b-xl sm:border-0 top-full hidden target:block peer dark:bg-gray-700"
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
    <section class="pt-20 pb-10 sm:pt-28 sm:pb-48 dark:bg-gray-800">
      <div
        class="container flex flex-col items-center gap-x-8 lg:flex-row mx-auto"
      >
        <div class="flex flex-col justify-center items-center">
          <h1
            class="text-3xl sm:text-5xl font-black tracking-tight dark:text-indigo-200"
          >
            Your
            <span
              class="bg-gradient-to-r from-blue-600 to-violet-600 bg-clip-text text-transparent"
              >VS Code</span
            >

            Boost
          </h1>
          <p
            class="mt-2 sm:mt-4 px-10 sm:px-0 text-center sm:text-left text-lg text-gray-600 dark:text-indigo-50"
          >
            Unlock your coding potential with tailored settings, shortcuts, and
            expert tutorials.
          </p>
          <div class="mt-6 sm:mt-8 flex gap-x-2">
            <a
              href=""
              class="px-6 py-2 sm:px-8 sm:py-3 text-lg font-semibold rounded-lg bg-indigo-600 text-indigo-50 hover:bg-indigo-700"
              >Explore</a
            >
            <a
              href=""
              class="px-6 py-2 sm:px-8 sm:py-3 text-lg font-semibold rounded-lg bg-gray-100 text-gray-900 hover:bg-gray-200 dark:bg-gray-300"
            >
              Learn More
            </a>
          </div>
        </div>
        <div class="relative w-2/3 mt-5 lg:mt-0">
          <div
            class="absolute -inset-2 rounded-xl top-10 left-10 bg-gradient-to-bl from-pink-300 to-blue-500 dark:from-gray-500 dark:to-gray-600 -rotate-z-3"
          ></div>
          <img
            src="/code_light.png"
            alt="Editor UI"
            class="rounded-2xl -rotate-z-3 pt-5 dark:hidden block"
          />
          <img
            src="/code_dark.png"
            alt="Editor UI"
            class="rounded-2xl -rotate-z-3 pt-5 hidden dark:block"
          />
        </div>
      </div>
    </section>
    <section
      class="bg-gray-100 flex flex-col gap-8 py-8 lg:py-8 sm:gap-12 dark:bg-gray-900"
      id="features"
    >
      <div class="container mx-auto max-w-screen-sm">
        <h2
          class="text-center font-bold sm:text-4xl text-2xl dark:text-indigo-100"
        >
          Unlock the full potential
        </h2>
        <p
          class="text-center mt-1 sm:mt-2 font-extralight sm:text-lg dark:text-indigo-50"
        >
          With tailored settings, keyboard shortcuts, and powerfull extensions,
          you can work smarter and faster.
        </p>
      </div>
      <div class="grid lg:grid-cols-3 gap-5 sm:gap-8 sm:px-20 px-4">
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-4 h-full dark:bg-gray-800 dark:border-indigo-700/70 dark:text-white"
          >
            <header class="flex flex-col gap-3">
              <Cog6ToothIcon class="sm:size-12 size-10 text-indigo-500" />
              <h3 class="font-bold py-2">Settings</h3>
            </header>
            <p class="font-extralight text-lg">
              Personalize your workspace to math your unique coding style and
              preferences effortlessly.
            </p>
          </article>
        </a>
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-6 h-full dark:bg-gray-800 dark:border-indigo-700/70 dark:text-white"
          >
            <header class="flex flex-col gap-3">
              <FireIcon class="sm:size-12 size-10 text-indigo-500" />
              <h3 class="font-bold py-2">Keyboard Shorcuts</h3>
            </header>
            <p class="font-extralight text-lg">
              Streamline your workflow with essentioal shortcuts that save you
              time and boost your skills.
            </p>
          </article>
        </a>
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-6 h-full dark:bg-gray-800 dark:border-indigo-700/70 dark:text-white"
          >
            <header class="flex flex-col gap-3">
              <PuzzlePieceIcon class="sm:size-12 size-10 text-indigo-500" />
              <h3 class="font-bold py-2">Exetensions</h3>
            </header>
            <p class="font-extralight text-lg">
              Expand your capabilities with powerfull wxtensions tailored to
              enhance your coding experirnce.
            </p>
          </article>
        </a>
      </div>
    </section>
    <section
      class="flex flex-col items-center sm:py-16 py-8 dark:bg-gray-700 dark:text-white"
    >
      <h2 class="text-center font-bold sm:text-4xl text-2xl">Stay Updated</h2>
      <p class="text-center font-extralight mt-1 px-10">
        Subscribe to our newsletters for the latest updates and tips.
      </p>
      <div class="container">
        <form class="flex justify-center gap-4 mt-5">
          <input
            type="email"
            class="border border-gray-500 rounded-xl w-1/2 px-3 placeholder:text-gray-400 focus:border-indigo-500 focus:outline-0"
            placeholder="Your Email"
          />
          <button
            class="bg-indigo-500 px-6 py-2 rounded-xl text-indigo-100 hover:bg-indigo-600"
          >
            <PaperAirplaneIcon class="block sm:hidden size-5" />
            <span class="hidden sm:inline">Subscribe</span>
          </button>
        </form>
      </div>
    </section>
  </main>
  <footer
    class="bg-indigo-600 text-white font-extralight py-2 sm:pt-10 sm:px-4 dark:bg-indigo-900"
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
