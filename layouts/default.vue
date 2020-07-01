<template>
  <div class="min-h-screen bg-gray-900 text-white font-sans">
    <navbar/>
    <Nuxt />
  </div>
</template>

<script>
import navbar from "~/components/common/navbar";
export default {
  components:{
    navbar
  }
}
</script>

