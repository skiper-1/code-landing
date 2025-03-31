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
  </main>
</template>
