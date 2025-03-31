<script setup>
import {
  CodeBracketSquareIcon,
  FireIcon,
  PuzzlePieceIcon,
  Cog6ToothIcon,
} from '@heroicons/vue/24/solid';
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
    <section class="pt-28 pb-48">
      <div class="container flex gap-x-8 mx-auto">
        <div class="flex flex-col justify-center">
          <h1 class="text-5xl font-black tracking-tight">
            Your

            <span
              class="bg-gradient-to-r from-purple-600 to-indigo-600 bg-clip-text text-transparent"
              >VS Code</span
            >

            Boost
          </h1>

          <p class="mt-4 text-lg text-gray-600">
            Unlock your coding potential with tailored settings, shortcuts, and
            expert tutorials.
          </p>

          <div class="mt-8 flex gap-x-2">
            <a
              href="#"
              class="px-8 py-3 text-lg font-semibold rounded-lg bg-indigo-600 text-indigo-50 hover:bg-indigo-700"
              >Explore</a
            >

            <a
              href="#features"
              class="px-8 py-3 text-lg font-semibold rounded-lg bg-gray-100 text-gray-900 hover:bg-gray-200"
            >
              Learn More
            </a>
          </div>
        </div>

        <div class="relative w-1/2 flex items-center">
          <div class="hero-reflection"></div>
          <img src="/img.png" alt="Editor UI" class="hero-image" />
        </div>
      </div>
    </section>
    <section class="bg-gray-100 flex flex-col gap-5 py-16" id="features">
      <div class="container mx-auto max-w-screen-sm">
        <h2 class="text-center font-bold text-4xl">
          Unlock the full potential
        </h2>
        <p class="text-center mt-5 font-extralight">
          With tailored settings, keyboard shortcuts, and powerfull extensions,
          you can work smarter and faster.
        </p>
      </div>
      <div class="grid grid-cols-3 gap-5 px-20">
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-6 h-full"
          >
            <header class="flex flex-col gap-3">
              <Cog6ToothIcon class="size-12 text-indigo-500" />
              <h3 class="font-bold">Settings</h3>
            </header>
            <p class="font-extralight mb-1 text-lg text-gray-500">
              Personalize your workspace to math your unique coding style and
              preferences effortlessly.
            </p>
          </article>
        </a>
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-6 h-full"
          >
            <header class="flex flex-col gap-3">
              <FireIcon class="size-12 text-indigo-500" />
              <h3 class="font-bold">Keyboard Shorcuts</h3>
            </header>
            <p class="font-extralight mb-1 text-lg text-gray-500">
              Streamline your workflow with essentioal shortcuts that save you
              time and boost your skills.
            </p>
          </article>
        </a>
        <a href="#">
          <article
            class="hover:border-indigo-500 bg-white rounded-xl border border-gray-200 p-6 h-full"
          >
            <header class="flex flex-col gap-3">
              <PuzzlePieceIcon class="size-12 text-indigo-500" />
              <h3 class="font-bold">Exetensions</h3>
            </header>
            <p class="font-extralight mb-1 text-lg text-gray-500">
              Expand your capabilities with powerfull wxtensions tailored to
              enhance your coding experirnce.
            </p>
          </article>
        </a>
      </div>
    </section>
    <section class="pt-10 pb-10">
      <h1 class="text-center font-bold text-3xl">Stay Updated</h1>
      <p class="text-center font-extralight mt-2">
        Subscribe to outr newsletters for the latest updates and tips.
      </p>
      <div class="flex justify-center gap-4 mt-5">
        <input
          type="text"
          class="border border-gray-500 rounded-xl w-1/2 px-3 placeholder:text-gray-400"
          placeholder="Your email"
        />
        <button
          class="bg-indigo-500 px-5 py-2 rounded-xl text-indigo-100 hover:bg-indigo-600"
        >
          Subscribe
        </button>
      </div>
    </section>
  </main>
  <footer class="bg-indigo-900 text-white font-extralight pt-10 px-20">
    <div class="flex items-center">
      <div class="w-1/2 flex flex-col gap-5">
        <a href="#" class="flex items-center gap-2">
          <CodeBracketSquareIcon class="size-12 text-white -rotate-10" />
          <span class="text-xl font-bold">Code Editor</span>
        </a>
        <p class="">
          Unlock your coding potential with tailored settings, shortcuts, and
          expert tutorials.
        </p>
      </div>
      <div class="flex justify-evenly items-center gap-5 w-1/2">
        <div class="flex flex-col gap-5">
          <h2 class="font-medium">Popular playlists</h2>
          <ul class="flex flex-col gap-3">
            <li class="hover:text-indigo-500">Prettier</li>
            <li class="hover:text-indigo-500">GitLens</li>
            <li class="hover:text-indigo-500">Live Share</li>
          </ul>
        </div>
        <div class="flex flex-col gap-5">
          <h2 class="font-medium">Configurations</h2>
          <ul class="flex flex-col gap-3">
            <li class="hover:text-indigo-500">Settings</li>
            <li class="hover:text-indigo-500">Keybinding</li>
            <li class="hover:text-indigo-500">Snippets</li>
          </ul>
        </div>
        <div class="flex flex-col items-center gap-5">
          <h2 class="font-medium">Social</h2>
          <ul class="flex flex-col items-center gap-1">
            <li class="hover:text-indigo-500 flex items-center gap-2 w-full">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 576 512"
                class="size-8"
              >
                <path
                  fill="white"
                  d="M549.7 124.1c-6.3-23.7-24.8-42.3-48.3-48.6C458.8 64 288 64 288 64S117.2 64 74.6 75.5c-23.5 6.3-42 24.9-48.3 48.6-11.4 42.9-11.4 132.3-11.4 132.3s0 89.4 11.4 132.3c6.3 23.7 24.8 41.5 48.3 47.8C117.2 448 288 448 288 448s170.8 0 213.4-11.5c23.5-6.3 42-24.2 48.3-47.8 11.4-42.9 11.4-132.3 11.4-132.3s0-89.4-11.4-132.3zm-317.5 213.5V175.2l142.7 81.2-142.7 81.2z"
                />
              </svg>
              <h2>YouTube</h2>
            </li>
            <li class="hover:text-indigo-500 flex gap-2 items-center w-full">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 496 512"
                class="size-8"
              >
                <path
                  fill="white"
                  d="M248 8C111 8 0 119 0 256S111 504 248 504 496 393 496 256 385 8 248 8zM363 176.7c-3.7 39.2-19.9 134.4-28.1 178.3-3.5 18.6-10.3 24.8-16.9 25.4-14.4 1.3-25.3-9.5-39.3-18.7-21.8-14.3-34.2-23.2-55.3-37.2-24.5-16.1-8.6-25 5.3-39.5 3.7-3.8 67.1-61.5 68.3-66.7 .2-.7 .3-3.1-1.2-4.4s-3.6-.8-5.1-.5q-3.3 .7-104.6 69.1-14.8 10.2-26.9 9.9c-8.9-.2-25.9-5-38.6-9.1-15.5-5-27.9-7.7-26.8-16.3q.8-6.7 18.5-13.7 108.4-47.2 144.6-62.3c68.9-28.6 83.2-33.6 92.5-33.8 2.1 0 6.6 .5 9.6 2.9a10.5 10.5 0 0 1 3.5 6.7A43.8 43.8 0 0 1 363 176.7z"
                />
              </svg>
              <h2>Telegram</h2>
            </li>
            <li class="hover:text-indigo-500 flex items-center gap-2 w-full">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 496 512"
                class="size-8"
              >
                <path
                  fill="white"
                  d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3 .3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5 .3-6.2 2.3zm44.2-1.7c-2.9 .7-4.9 2.6-4.6 4.9 .3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3 .7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3 .3 2.9 2.3 3.9 1.6 1 3.6 .7 4.3-.7 .7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3 .7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3 .7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
                />
              </svg>
              <h2>GitHub</h2>
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
