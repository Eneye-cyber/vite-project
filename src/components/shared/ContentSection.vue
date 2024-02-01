<script setup lang="ts">
interface Props {
  title: string,
  img: string,
  width?: string,
  height?: string,
  reverse?: boolean
}
const props = defineProps<Props>()
</script>

<template>
  <section class="">
    <div class="container px-[5%] flex justify-between items-center gap-12" :class="props.reverse && 'flex-row-reverse'">
      <img :src="props.img" :width="props.width ?? '542px'" :height="height ?? '320px'" :alt="props.title" loading="lazy">
      <div class="content_text text-left mt-10 max-w-[443px]">
        <h3 class=" text-2xl font-semibold">{{props.title}}</h3>
        <slot></slot>
        
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>
