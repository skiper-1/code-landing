<script setup>
import { CodeBracketSquareIcon } from '@heroicons/vue/24/solid';
import Playlists from './Playlists.vue';
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
              href=""
              class="px-8 py-3 text-lg font-semibold rounded-lg bg-indigo-600 text-indigo-50 hover:bg-indigo-700"
              >Explore</a
            >
            <a
              href=""
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
    <section class="container mx-auto py-16">
      <h2 class="text-center font-bold text-3xl">Stay Updated</h2>
      <p class="text-center font-extralight mt-2 text-gray-500">
        Subscribe to our newsletters for the latest updates and tips.
      </p>
      <div class="container">
        <form class="flex justify-center gap-4 mt-5">
          <input
            type="email"
            class="border border-gray-500 rounded-xl w-1/2 px-3 placeholder:text-gray-400 focus:border-indigo-500 focus:ring-1 shadow-sm"
            placeholder="Your Email"
          />
          <button
            class="bg-indigo-500 px-6 py-2 rounded-xl text-indigo-100 hover:bg-indigo-600"
          >
            Subscribe
          </button>
        </form>
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
  <Playlists />
</template>
