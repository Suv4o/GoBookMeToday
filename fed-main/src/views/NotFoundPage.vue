<script lang="ts">
export default {
  name: 'NotFoundPage',
}
</script>

<template>
  <div class="default-container">
    <div class="h-[70vh] px-4 py-16 sm:px-6 sm:py-24 grid place-items-center lg:px-8">
      <div class="max-w-max mx-auto">
        <div class="sm:flex">
          <p class="text-4xl font-extrabold text-teal-600 sm:text-5xl">404</p>
          <div class="sm:ml-6">
            <div class="sm:border-l sm:border-gray-200 sm:pl-6">
              <h1 class="text-4xl font-extrabold text-gray-900 tracking-tight sm:text-5xl">Page not found</h1>
              <p class="mt-1 text-base text-gray-500">Please check the URL in the address bar and try again.</p>
            </div>
            <div class="mt-10 flex space-x-3 sm:border-l sm:border-transparent sm:pl-6">
              <router-link
                :to="{ name: 'home' }"
                class="inline-flex items-center px-4 py-2 border border-transparent text-sm font-medium rounded-md shadow-sm text-white bg-teal-600 hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-500"
              >
                Go back home
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
