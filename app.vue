

<template>
  <div class="w-full min-h-screen bg-gray-950">

    <!-- Navigation -->
    <div class="max-w-screen-lg mx-auto pt-5 px-5 flex justify-center font-bold font-Lalezar-Regular">
      <div class="flex gap-16 text-gray-400 text-md md:text-xl">
        <NuxtLink to="/">خانه</NuxtLink>
        <NuxtLink to="/form">درباره ما</NuxtLink>
        <NuxtLink to="/guidelines">راهنما</NuxtLink>
      </div>
    </div>

    <!-- Main Content -->
    <div class="max-w-screen-lg mx-auto text-center px-4 pt-32">
      <p class="font-Lalezar-Regular font-extrabold tracking-tight text-gray-300 text-3xl md:text-6xl">رفع تعهد با ارز و بدون ارز
      </p>

      <p class="mt-4 mb-8 px-4 text-sm md:text-md md:px-48 text-gray-400">
        تیم ما با ارائه مشاوره و خدمات تخصصی در زمینه رفع تعهد ارزی، همواره در کنار شماست تا این فرآیند به ساده‌ترین،
        سریع‌ترین و مطمئن‌ترین شکل ممکن انجام شود. ما با دانش به‌روز و تجربه عملی، تمام مراحل اداری و مالی را برای شما
        تسهیل می‌کنیم تا بدون دغدغه تمرکز خود را بر توسعه تجارت خود بگذارید
      </p>

      <!-- Button to Trigger Modal -->
      <div
        class="inline-flex justify-center items-center gap-2 border border-gray-300 rounded-lg py-3 px-5 cursor-pointer max-w-fit"
        @click="showModal = true">
        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 512 512">
          <mask id="circleFlagsIr0">
            <circle cx="256" cy="256" r="256" fill="#fff" />
          </mask>
          <g mask="url(#circleFlagsIr0)">
            <path fill="#eee" d="M0 144.7L258.8 39.6L512 144.7v222.6L257 493L0 367.3z" />
            <path fill="#6da544"
              d="M0 0v144.7h105.6v-22.2h33.6v22.2h33.3v-22.2h33.6v22.2h33.3v-22.2H273v22.2h33v-22.2h33.6v22.2h33.2v-22.2h33.6v22.2H512V0z" />
            <path fill="#d80027"
              d="M0 367.3V512h512V367.3H406.4v22.4h-33.6v-22.4h-33.2v22.4H306v-22.4h-33v22.4h-33.6v-22.4h-33.3v22.4h-33.6v-22.4h-33.3v22.4h-33.6v-22.4zm339.1-178h-33.4c.2 3.7.4 7.4.4 11.1c0 24.8-6.2 48.8-17 66c-3.3 5.2-9 12.6-16.4 17.6v-94.7h-33.4v94.8c-7.5-5-13-12.4-16.4-17.7c-10.8-17-17-41-17-65.9c0-3.7.2-7.4.4-11H173a190 190 0 0 0-.4 11c0 68.7 36.7 122.5 83.5 122.5s83.5-53.8 83.5-122.5c0-3.7-.1-7.4-.4-11z" />
          </g>
        </svg>
        <p class="font-medium text-gray-400 text-sm md:text-md">ارتباط با مشاور برای تجار ایرانی</p>
      </div>

    </div>

    <!-- Modal Section (conditionally rendered) -->
    <div v-if="showModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 m-5">
      <div class="bg-white rounded-lg w-full max-w-lg p-6 relative">

        <!-- Close Button -->
        <button @click="showModal = false" class="absolute top-4 right-4 text-gray-500 hover:text-gray-700">
          ✖️
        </button>

        <!-- Modal Content -->
        <div class="text-center">
          <h2 class="md:text-xl font-bold mb-4">محمدحسین محمدی، مشاور ارشد بازرگانی</h2>

          <p class="mb-6">
            ما در کنار شما هستیم تا به سؤالات شما در زمینه بازرگانی و تجارت پاسخ دهیم و فرآیندهای مربوط به
            توسعه کسب‌وکار را ساده تر کنیم
          </p>

          <!-- WhatsApp Button -->
          <div class="flex items-center justify-center mb-6">
            <a href="https://wa.me/+989199374770" target="_blank"
              class="flex items-center px-4 py-2 bg-green-500 text-white rounded-lg hover:bg-green-600">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="mr-2"
                viewBox="0 0 16 16">
                <path
                  d="M13.601 2.326A7.85 7.85 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.9 7.9 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.9 7.9 0 0 0 13.6 2.326zM7.994 14.521a6.6 6.6 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.56 6.56 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592m3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.73.73 0 0 0-.529.247c-.182.198-.691.677-.691 1.654s.71 1.916.81 2.049c.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232" />
              </svg>
              تماس با من در واتسپ
            </a>
          </div>

        </div>
      </div>
    </div>

  </div>
</template>

<script setup>
// Import Vue ref
import { ref } from 'vue';

// Define state variable to control modal visibility
const showModal = ref(false);
</script>

<style scoped>
/* Scoped styling if needed */
</style>
