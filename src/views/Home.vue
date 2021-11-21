<template>
  <logo/>
  <navbar/>
  <landing/>
</template>

<script>
// @ is an alias to /src
import logo from "@/components/header.vue";
import navbar from "@/components/navbar.vue";
import landing from '@/components/landing.vue';

export default {
  name: "Home",
  components: {
    logo,
    navbar,
    landing
  },
};
</script>
