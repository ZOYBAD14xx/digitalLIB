<template>
<b-col md="3">
    <b-card
    :title=title
    :img-src=img_src
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem"
    class="mb-2"
  >
    <b-card-text> Lorem ipsum dolor sit amet, consectetur adipisicing elit. </b-card-text>
    <b-card-text>
      <p><b>xxx,xxx kip</b></p>
      <p id="discount">xxx,xxx kip</p>
      <b-badge pill variant="success">Popular</b-badge>
    </b-card-text>
  </b-card>
</b-col>
</template>

<script>
export default {
 props: {
    title: {
      type: String,
      require: true,
    },
    img_src: {
      type: String,
      require: true,
    },

  },
};
</script>

<style>
#discount {
  text-decoration: line-through;
}
</style>
