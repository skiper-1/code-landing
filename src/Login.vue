<script setup>
import { CodeBracketSquareIcon } from '@heroicons/vue/24/solid';
</script>

<template>
  <main>
    <section
      class="flex flex-col items-center gap-6 pt-5 bg-gray-50 min-h-screen dark:bg-gray-800 dark:text-white"
    >
      <a href="#">
        <CodeBracketSquareIcon class="size-16 text-indigo-500 -rotate-6" />
      </a>
      <div
        class="border border-gray-300 w-full sm:w-fit rounded-lg bg-white p-6 dark:bg-gray-900 dark:border-none"
      >
        <form action="" class="flex flex-col gap-6">
          <div class="flex flex-col gap-1">
            <label for="email">Email</label>
            <input
              type="email"
              id="email"
              class="border rounded-lg border-gray-300 px-4 py-2 focus:border-indigo-500 outline-none dark:border-gray-600"
              placeholder="Enter email"
            />
          </div>
          <div class="flex flex-col">
            <label for="password">Password</label>
            <input
              type="password"
              id="password"
              class="border rounded-lg border-gray-300 px-4 py-2 focus:border-indigo-500 outline-none dark:border-gray-600"
              placeholder="Enter password"
            />
          </div>

          <button
            class="bg-indigo-500 text-white rounded-lg mt-2 py-2 px-6 hover:bg-indigo-700"
          >
            Log In
          </button>
        </form>
        <p class="mt-8 text-sm text-center">
          Don't have an account?
          <a href="#" class="text-indigo-500 hover:text-indigo-700">
            Sign Up
          </a>
        </p>
      </div>
    </section>
  </main>
</template>
