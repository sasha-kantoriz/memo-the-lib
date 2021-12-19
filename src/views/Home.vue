<template>
  <navbar/>
  <landing/>
</template>

<script>
// @ is an alias to /src
import navbar from "@/components/navbar.vue";
import landing from '@/components/landing.vue';

export default {
  name: "Home",
  components: {
    navbar,
    landing
  },
};
</script>
