<script setup>
import {
  CodeBracketSquareIcon,
  Bars3Icon,
  XMarkIcon,
} from '@heroicons/vue/24/solid';
</script>

<template>
  <header
    class="container mx-auto p-2 sm:py-4 fixed top-0 inset-x-0 sm:static z-10 border-b sm:border-0 bg-white"
  >
    <div class="container flex items-center justify-between gap-10">
      <a href="#" class="flex items-center gap-1 sm:gap-2">
        <CodeBracketSquareIcon
          class="size-10 sm:size-12 text-indigo-500 -rotate-10"
        />
        <span class="text-xl sm:text-3xl font-bold">Code Editor</span>
      </a>
      <nav class="grow hidden sm:block">
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
      <div class="flex sm:hidden">
        <nav
          id="nav"
          class="absolute inset-x-0 bg-white border-b sm:border-0 top-full hidden target:block peer"
        >
          <ul class="flex flex-col items-center gap-2 px-3 pb-3">
            <li class="w-full">
              <a
                href="#nav"
                class="inline-block w-full p-2 text-center rounded hover:bg-gray-100"
                >Library</a
              >
            </li>
            <li class="w-full">
              <a
                href="#"
                class="inline-block w-full p-2 text-center rounded hover:bg-gray-100"
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
          class="hover:bg-gray-100 p-2 rounded-md peer-target:hidden"
        >
          <Bars3Icon class="size-10 block sm:hidden" />
        </a>
        <a
          href="#"
          class="hidden hover:bg-gray-100 p-2 rounded-md peer-target:block"
        >
          <XMarkIcon class="size-10" />
        </a>
      </div>
    </div>
  </header>

  <main>
    <section class="flex flex-col pt-24 pb-6 sm:py-16 sm:gap-y-12 gap-y-8">
      <div class="container mx-auto max-w-screen-sm">
        <h1 class="text-4xl sm:text-5xl font-black text-center">Playlists</h1>
        <p class="text-center font-extralight text-lg mt-2">
          Learn how to make VSCode work for you with our comprehensive guides
          and tutorials.
        </p>
      </div>
      <div
        class="container mx-auto grid sm:grid-cols-3 gap-y-4 grid-cols-1 sm:gap-8"
      >
        <div class="sm:col-span-1 flex flex-col gap-y-6">
          <input
            type="search"
            placeholder="Playlist title"
            class="border rounded-xl border-gray-300 px-4 py-2 focus:border-indigo-500 focus:ring-1"
          />
          <div class="flex flex-col gap-2 px-4">
            <h3 class="font-bold text-lg">Tags</h3>
            <ul class="font-extralight flex flex-col gap-1">
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Productivity
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Development
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Design
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Utility
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Integration
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Testing
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Debugging
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Formatting
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Collaboration
                </button>
              </li>
              <li>
                <button
                  class="w-full px-3 py-2 text-left text-sm rounded-xl hover:bg-gray-100"
                >
                  Documentation
                </button>
              </li>
            </ul>
          </div>
        </div>
        <div
          class="col-span-2 grid sm:grid-cols-2 xl:grid-cols-3 grid-cols-1 gap-4 px-4"
        >
          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">Prettier</h3>
              </header>
              <p class="mt-2 mb-6">
                Automatically format your code to ensure consistent style across
                your project.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Utility
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Formatting
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">GitLens</h3>
              </header>
              <p class="mt-2 mb-6">
                Supercharge Git within VS Code with commit vizualization and
                blame annotation.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Collaboration
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">Live Share</h3>
              </header>
              <p class="mt-2 mb-6">
                Real-time collaborative development from the comfort of your
                favourite editor.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Collaboration
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">ESLint</h3>
              </header>
              <p class="mt-2 mb-6">
                Find and fix porblems in your JavaScript/TypeScript code
                automatically.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Debugging
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">Code Runner</h3>
              </header>
              <p class="mt-2 mb-6">
                Run code snippets in multiple programming languages with a
                single click.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Utility
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">REST Client</h3>
              </header>
              <p class="mt-2 mb-6">
                Send HTTP requests and view responses directly in Visual studio
                Code.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Utility
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">Code Spell Checker</h3>
              </header>
              <p class="mt-2 mb-6">
                Cathc common spelling errors in your sourse code and
                documentation.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Utility
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Documentation
                  </li>
                </ul>
              </footer>
            </article>
          </a>

          <a href="#">
            <article
              class="flex flex-col h-full border border-gray-300 rounded-xl p-6 hover:border-indigo-600"
            >
              <header>
                <h3 class="font-semibold text-lg">Docker</h3>
              </header>
              <p class="mt-2 mb-6">
                Manage Docker containers and Images directly from VS Code.
              </p>
              <footer class="mt-auto">
                <ul class="flex gap-2 flex-wrap">
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Development
                  </li>
                  <li
                    class="bg-indigo-100 rounded-xl px-3 py-1 text-indigo-600"
                  >
                    Integration
                  </li>
                </ul>
              </footer>
            </article>
          </a>
        </div>
      </div>
    </section>
  </main>
  <footer
    class="bg-indigo-900 text-white font-extralight py-2 sm:pt-10 sm:px-4"
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
