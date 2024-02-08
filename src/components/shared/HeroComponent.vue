<script setup lang="ts">
</script>

<template>
  <section class="py-[100px]">
    <div class="container px-[5%] text-center flex flex-col gap-12">
        <div class="hero-text">
          <slot default>
            <h1 class=" text-[80px] font-semibold"><span class="text-default">Productivity</span> Report</h1>
            <p class="text-lg font-light">Performa Insight's in-depth analysis and reporting tools</p>
          </slot>
        </div>
        <div class="btn-group">
            <button class="bg-default text-lg font-semibold text-white px-6 py-3 rounded-lg cursor-pointer">Get Started Now</button>
            <button class="bg-transparent text-lg  px-6 py-3 cursor-pointer">Live Preview</button>
        </div>
        <img src="/img/Placeholder.png" class="shadow-lg shadow-blue-300" width="1296px" height="500px" alt="productivity report">
    </div>
  </section>
</template>

<style scoped>

</style>
