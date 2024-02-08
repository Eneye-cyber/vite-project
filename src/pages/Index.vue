<script setup lang="ts">
import HeroComponent from '../components/shared/HeroComponent.vue';
import { ref } from 'vue'

const pFeature = ref(1)



</script>

<template>
  <HeroComponent>
    <template #default>
      <h1 class=" text-[80px] font-semibold">A Software Solution for the <span class="text-default">Workplace</span></h1>
      <ul class="flex justify-center items-center gap-4">
        <li class="flex gap-2 items-start py-3">
          <img src="/img/Circle-check.png" alt="check">
          <p>Optimize your workflow</p>
        </li>

        <li class="flex gap-2 items-start py-3">
          <img src="/img/Circle-check.png" alt="check">
          <p>Optimize your workflow</p>
        </li>

        <li class="flex gap-2 items-start py-3">
          <img src="/img/Circle-check.png" alt="check">
          <p>Optimize your workflow</p>
        </li>
      </ul>
    </template>
  </HeroComponent>

  <article class="py-[20px] px-[5%]">
    <div class="text-center flex flex-col gap-32">
      <div class="container flex flex-col gap-32">
        <div class="max-w-[820px] mx-auto">
            <h1 class=" text-[48px] font-semibold text-gradient-1">Measure your productivity</h1>
            <p class="text-lg">Measure your productivity and give your employees a good time at work daily</p>
        </div>

        <div class="grid grid-cols-2 gap-20 items-start">
          <div class="text-justify pr-6 flex-col flex gap-10">
            <div>
              <h3 @click="pFeature = 1" class="text-4xl font-semibold text-[#7f76b399] cursor-pointer" :class="pFeature === 1 && ' text-gradient-1'">Workforce Optimization</h3>
              <template v-if="pFeature === 1">
                <p class="mt-3">Performa insight provides tools and metrics to assess employee productivity, efficiency, and effectiveness in achieving tasks and goals within an organization. It offers insights to identify areas for improvement and optimize resource allocation for enhanced overall performance</p>
                <div class="mt-5">
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Productivity</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Efficiency</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg">Effectiveness</span>
                </div>

              </template>
            </div>

            <div>
              <h3 @click="pFeature = 2" class="text-4xl font-semibold  cursor-pointer" :class="pFeature === 2 ? ' text-default font-black opacity-75' : 'text-[#7f76b399]'">Real-time Monitoring</h3>
              <template v-if="pFeature === 2">
                <p class="mt-3">Performa insight provides tools and metrics to assess employee productivity, efficiency, and effectiveness in achieving tasks and goals within an organization. It offers insights to identify areas for improvement and optimize resource allocation for enhanced overall performance</p>
                <div class="mt-5">
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Productivity</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Efficiency</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg">Effectiveness</span>
                </div>

              </template>
            </div>

            <div>
              <h3 class="text-4xl font-semibold text-[#7f76b399]">Workforce Optimization</h3>
              <!-- <p class="mt-3">Performa insight provides tools and metrics to assess employee productivity, efficiency, and effectiveness in achieving tasks and goals within an organization. It offers insights to identify areas for improvement and optimize resource allocation for enhanced overall performance</p>
              <div class="mt-5">
                <span class="inline-block px-3 py-2 border border-blue-300 box-shadow">Productivity</span>
              </div> -->
            </div>
          </div>

          <div class="relative">
            <img src="https://clickup.com/assets/home-test/collaborate.png" alt="">
          </div>
        </div>

        <div class="grid grid-cols-2 gap-20 items-center">
          <div class="relative">
            <img src="https://clickup.com/assets/home-test/collaborate.png" alt="">
          </div>


          <div class="text-justify pr-6 flex-col flex gap-10">
            <div>
              <h3 class="text-4xl font-semibold text-gradient-1 cursor-pointer">Workforce Optimization</h3>
                <p class="mt-3">Performa insight provides tools and metrics to assess employee productivity, efficiency, and effectiveness in achieving tasks and goals within an organization. It offers insights to identify areas for improvement and optimize resource allocation for enhanced overall performance</p>
                <div class="mt-5">
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Productivity</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Efficiency</span>
                  <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg">Effectiveness</span>
                </div>
            </div>

          </div>

          
        </div>

        <div class="grid grid-cols-2 gap-20 items-center">
          <div class="text-justify pr-6 flex-col flex gap-10">
            <div>
              <h3 class="text-4xl cursor-pointer  text-default font-black opacity-75" >Workforce Optimization</h3>
              <p class="mt-3">Performa insight provides tools and metrics to assess employee productivity, efficiency, and effectiveness in achieving tasks and goals within an organization. It offers insights to identify areas for improvement and optimize resource allocation for enhanced overall performance</p>
              <div class="mt-5">
                <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Productivity</span>
                <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg mr-3">Efficiency</span>
                <span class="inline-block px-3 py-2 border border-blue-300 shadow-lg">Effectiveness</span>
              </div>

            </div>

          </div>

          <div class="relative">
            <img src="https://clickup.com/assets/home-test/collaborate.png" alt="">
          </div>
        </div>
      </div>  
    </div>
  </article>

  <article class="py-[150px] px-[5%]">
    <div class="text-center flex flex-col gap-32">
      <div class="container flex flex-col gap-8">
        <div class="max-w-[820px] mx-auto">
          <p class="text-light ">OUR SOLUTIONS</p>
            <h1 class=" text-[40px] font-semibold">Take your Business to the next level with our <span class="text-default">Digital Solutions</span></h1>
        </div>

        <section>
          <div  class="tabs-menu-2 mx-auto">
            <a href="#" class="tabreg w-inline-block w-tab-link w--current">Spot Burnout & Disengagement</a>
            <a href="#" class="tabreg w-inline-block w-tab-link ">Employee Activity Pulse</a>
            <a href="#" class="tabreg w-inline-block w-tab-link ">Api Integration</a>
            <a href="#" class="tabreg w-inline-block w-tab-link ">Application and Website Usage</a>
          </div>

          <div class=" hidden">
            https://www.myworkpay.com/
            https://clickup.com/
          </div>
        </section>

      </div>  
    </div>
  </article>
</template>

<style scoped>
.text-gradient-1{
  background: linear-gradient(269deg,#fa12e3 1.83%,#7612fa 53.68%,#12d0fa 106.48%);
  -webkit-background-clip: text;
  background-clip: text;
  font-weight: 900;
  -webkit-text-fill-color: transparent;
}
.tabs-menu-2 {
    width: fit-content;
    color: #253545;
    text-align: center;
    border-bottom: 1px solid rgba(0,0,0,.1);
    justify-content: center;
    margin-top: 40px;
    display: flex;
}
.w-tab-link {
    vertical-align: top;
    text-align: left;
    cursor: pointer;
    color: #222;
    background-color: #ddd;
    padding: 9px 30px;
    text-decoration: none;
    display: inline-block;
    position: relative;
}
.tabreg {
    color: rgba(37,53,69,.7);
    background-color: #fff;
    font-size: 16px;
    font-weight: 400;
    line-height: 26px;
}
.tabreg.w--current {
  @apply text-default border-b border-default opacity-75;
    background-color: #fff;
    flex: 0 auto;
    font-size: 16px;
}
</style>
