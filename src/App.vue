<template>
  <div class="min-h-screen bg-gray-800">
    <Header />
    <FeatureCards />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/HeaderPage.vue";
import FeatureCards from "./components/FeatureCards.vue";
import Footer from "./components/FooterPage.vue";

export default {
  components: { Header, FeatureCards, Footer }
};
</script>
