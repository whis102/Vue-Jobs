<script setup>
import HeroSection from "@/components/HeroSection.vue";
import Home from "@/components/Home.vue";
import JobList from "@/components/JobList.vue";
</script>

<template>
  <HeroSection />
  <Home />
  <JobList :limit="6" :showButton="true" />
</template>
