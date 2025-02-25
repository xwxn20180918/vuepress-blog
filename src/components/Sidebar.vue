<template>
  <section>
    <div class="flex items-center font-600 font-size-[1.2rem]">
      <!--<img :src="{astroLogo}" alt="暂无图片" />-->
      <img
        src="src/assets/astro.svg"
        width="40"
        height="40"
        alt="暂无图片"
      />
      <h1 class="ml-2 text-gray-800 dark:text-gray-200">老油条周刊</h1>
    </div>
    <ul>
      <li>
        <a href="/a">to a</a>
      </li>
      <li>
        <a href="/b">to b</a>
      </li>
    </ul>
  </section>
</template>

<script setup lang="ts">
import { computed, onMounted, watch } from 'vue';

computed(() => {});

onMounted(() => {});
</script>

<style lang="less" scoped></style>
