<template>
  <div class="w-full h-full min-h-screen bg-linear-to-b from-white to-amber-50 pb-3">
    <!-- 顶部导航 -->
    <header
      class="sticky top-0 transition-all bg-white bg-opacity-80 backdrop-blur-lg z-10 w-full mx-auto flex flex-col justify-center items-center shadow-sm pt-0"
    >
      <div
        class="max-w-7xl w-full mx-auto py-2 px-4 sm:px-10 flex flex-row justify-between items-center"
      >
        <div class="flex justify-start items-center">
          <a href="/">
            <div class="cursor-pointer flex flex-row justify-start items-center hover:opacity-80">
              <img src="/logo.svg" class="h-9 sm:h-10 w-auto mr-2" alt="" />
              <h1 class="text-2xl font-serif text-gray-500 italic">Ech0</h1>
            </div>
          </a>
        </div>
        <nav>
          <!-- github -->
          <a href="https://github.com/lin-snow/Ech0">
            <github class="w-8 h-8 text-gray-500 hover:text-gray-700 transition duration-300" />
          </a>
        </nav>
      </div>
    </header>

    <!-- 中间内容 -->
    <div class="my-8">
      <div class="w-full flex flex-col justify-center items-center px-4 sm:px-16">
        <h2
          class="w-full max-w-3xl text-center text-3xl sm:text-5xl font-serif font-medium mt-4 mb-4"
        >
          <span class="block sm:inline">开源自主托管 </span>
          <span class="block sm:inline">思想自由流动</span>
        </h2>
        <h3 class="w-full text-lg sm:text-2xl text-gray-600 text-center font-serif">
          随时书写，灵感不设边界
        </h3>
      </div>

      <div class="px-6 w-full max-w-7xl mx-auto">
        <div class="py-2 w-auto flex flex-row justify-center items-center gap-2 sm:gap-4">
          <a
            class="bg-orange-300 text-white w-32 py-2 rounded-md shadow-lg flex flex-row justify-center items-center hover:bg-orange-400"
            href="https://github.com/lin-snow/Ech0"
          >
            即刻体验
          </a>
        </div>
      </div>

      <div class="relative w-full sm:max-w-6xl mx-auto">
        <img
          class="block w-full h-auto"
          src="/screenshot.png"
          alt="demo-screenshot"
          style="min-width: 0"
          loading="lazy"
        />
      </div>
    </div>
    <!-- 底部导航 -->
    <div></div>
  </div>
</template>

<script setup lang="ts">
import github from '@/components/icons/github.vue'
</script>

<style scoped></style>
