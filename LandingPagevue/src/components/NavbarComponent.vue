<script setup lang="ts"></script>
<template>
  <nav class="flex justify-between px-6 py-2 items-center">
    <h1 class="invisible md:visible text-3xl font-bold">LO</h1>
    <div class="dropdown dropdown-end">
      <button tabindex="0" class="visible lg:invisible btn btn-square btn-ghost">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-8 h-8 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          ></path>
        </svg>
      </button>
      <ul tabindex="0" class="menu dropdown-content z-[1] p-2 shadow bg-base-100 rounded-box w-52">
        <li><a href="#">HOME</a></li>
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#article">ARTICLE</a></li>
        <li><a href="#subscribe">SUBSCRIBE</a></li>
      </ul>
    </div>
    <div class="hidden lg:block">
      <ul class="inline-flex gap-8 text-xl">
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#article">ARTICLE</a></li>
        <li><a href="#subscribe" class="outline outline-2 p-2">SUBSCRIBE</a></li>
      </ul>
    </div>
  </nav>
</template>
