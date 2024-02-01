<script setup lang="ts">
import AdBanner from '../shared/AdBanner.vue';
import ContentSection from '../shared/ContentSection.vue';


</script>

<template>
  <article class="py-[100px] px-[5%]">
    <div class="text-center flex flex-col gap-32">
      <div class="container flex flex-col gap-32">
        <div class="max-w-[820px] mx-auto">
            <h1 class=" text-[60px] font-semibold">Gain Valuable Insights into Employee’s Productivity Habits</h1>
            <p class="text-lg font-light">Provide tailored reports based on precise data</p>
        </div>
        <ContentSection title="Time Tracking" img="/img/Left.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Get detailed breakdown of time spent on various tasks, projects, or activities.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Check out a daily breakdown showing time spent on productive vs. unproductive activities.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Track productivity trends on a weekly, monthly, and yearly basis.</p>
            </li>
          </ul>
        </ContentSection>

        <ContentSection title="Activity Summary" reverse img="/img/Right.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Performa Insight gives overview of an individual's or team's activities within a specific timeframe.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It typically includes key metrics and insights to give you a quick understanding of your employee’s productivity levels.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It provides ability to customize the report based on preferences or specific requirements.</p>
            </li>
          </ul>
        </ContentSection>

        <ContentSection title="Application and website Usage" img="/img/Right.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Examine applications or software utilized throughout working hours.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Track websites visited and time spent on each site</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Make informed decisions to enhance overall efficiency and performance.</p>
            </li>
          </ul>
        </ContentSection>

        <ContentSection title="Activity Summary" reverse img="/img/Right.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Performa Insight gives overview of an individual's or team's activities within a specific timeframe.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It typically includes key metrics and insights to give you a quick understanding of your employee’s productivity levels.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It provides ability to customize the report based on preferences or specific requirements.</p>
            </li>
          </ul>
        </ContentSection>

      </div>

      <AdBanner />

      <div class="container flex flex-col gap-32">
        
        <ContentSection title="Time Tracking" img="/img/Left.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Get detailed breakdown of time spent on various tasks, projects, or activities.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Check out a daily breakdown showing time spent on productive vs. unproductive activities.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Track productivity trends on a weekly, monthly, and yearly basis.</p>
            </li>
          </ul>
        </ContentSection>

        <ContentSection title="Activity Summary" reverse img="/img/Right.png">
          <ul class="py-4">
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>Performa Insight gives overview of an individual's or team's activities within a specific timeframe.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It typically includes key metrics and insights to give you a quick understanding of your employee’s productivity levels.</p>
            </li>
            <li class="flex gap-2 items-start py-3">
              <img src="/img/Circle-check.png" alt="check">
              <p>It provides ability to customize the report based on preferences or specific requirements.</p>
            </li>
          </ul>
        </ContentSection>

      </div>

      <div class="btn-group">
          <button class="bg-default text-lg font-semibold text-white px-6 py-3 rounded-lg cursor-pointer">Get Started Now</button>
          <button class="bg-transparent text-lg  px-6 py-3 cursor-pointer">Live Preview</button>
        </div>
    </div>
  </article>
</template>

<style scoped>

</style>
