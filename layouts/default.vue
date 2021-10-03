<template>
  <div>
    <b-container>
      <topbar />
      <div class="Content">
        <nuxt />
      </div>
      <footbar />
    </b-container>
  </div>
</template>
<script>
import footbar from '../components/footbar.vue';
export default {
  components: { footbar },

};
</script>

<style>
.Content {
  margin-top: 20px;
}
body {
  background-color: #f8f9fa;
}

</style>
