<script>
export default {
  data() {
    return { 
      message: "Hello this is a Jumbotron",
      subMessage: "This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information."
    }
  }
}
</script>

<template>
    <div class="bg-white text-black py-20 px-6 text-center">
        <h1 class="text-5xl font-bold mb-4">{{ message }}</h1>
        <p class="text-lg mb-6">{{ subMessage }}</p>
        <div class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0">
            <a
            href="#"
            class="inline-flex justify-center items-center py-3 px-5 text-base font-medium text-center text-white rounded-lg bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900"
          >
            Iscriviti a Boolean
          </a>
          <a
            href="#"
            class="inline-flex justify-center items-center py-3 px-5 sm:ml-4 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300 hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
          >
            Leggi la documentazione
          </a>
        </div>
    </div>
</template>