<template>
  <div class="main-container">
    <Banner />
    <h1>Monte o seu hamburg:</h1>
    <BurgueForm />
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgueForm from '@/components/BurgueForm.vue';
export default {
  name: "Home",
  components: {
    Banner,
    BurgueForm
  }
}
</script>
