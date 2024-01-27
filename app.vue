<template>
  <div :class="{'dark': darkMode}">
    <sectiion>
      <div class="h-auto w-screen bg-sky-200">
        <nav class="font-inter h-auto w-full flex flex-row items-center justify-between p-4">
          <a href="https://breeze-templates.webflow.io/" aria-current="page" class="relative float-left bg-[#00000000] leading-[0] text-[#333333] no-underline hover:outline-0 max-[991px]:mr-auto max-[767px]:pl-0" aria-label="home">
            <img src="https://assets.website-files.com/6357722e2a5f19121d37f84d/6357722e2a5f198e9637f855_Group%2047874-2.png" loading="lazy" alt="" class="inline-block max-h-6 max-w-full" />
          </a>
          <div class="flex flex-row items-center justify-between gap-x-4">
            <NuxtLink to="/">首页</NuxtLink>
            <NuxtLink to="/price">价格</NuxtLink>
            <NuxtLink to="/about">关于</NuxtLink>
          </div>
          <!-- MENU CONTENT 2 -->
          <div class="flex flex-row space-x-3 items-center">
            <a href="https://tailwind-css-template-breeze.vercel.app/Login" class="font-inter rounded-lg lg:px-6 lg:py-4 lg:hover:text-gray-800">Sign Up</a>
            <a href="#" class="flex max-w-[300px] flex-row items-center border-2 border-black bg-white px-8 py-4 font-semibold text-black transition [box-shadow:rgb(0,_0,0)-8px_8px] hover:[box-shadow:rgb(171,_196,_245)_0px_0px]">
              <p class="mr-6 font-bold">Free Components</p>
              <svg fill="currentColor" class="h-4 w-4 flex-none" viewBox="0 0 20 21" xmlns="http://www.w3.org/2000/svg">
                <title>Arrow Right</title>
                <polygon points="16.172 9 10.101 2.929 11.515 1.515 20 10 19.293 10.707 11.515 18.485 10.101 17.071 16.172 11 0 11 0 9"></polygon>
              </svg>
            </a>
          </div>
        </nav>
      </div>
    </sectiion>
    <NuxtPage></NuxtPage>
  </div>
</template>

<script setup lang="ts">
import {ref} from "vue";

const darkMode = ref(false)

</script>