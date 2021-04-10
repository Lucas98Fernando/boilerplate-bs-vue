<template>
  <div>
    <Navbar />
    <Views />
    <Footer />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar/Navbar.vue";
import Views from "@/layout/Views.vue";
import Footer from "@/components/Footer/Footer.vue";

export default {
  name: "Index",
  components: {
    Navbar,
    Views,
    Footer,
  },
};
</script>
