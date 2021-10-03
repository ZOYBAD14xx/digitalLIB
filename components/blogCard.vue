<template>
  <b-col md="3" class="mt-2">
    <nuxt-link to="#" style="text-decoration: none; color: inherit">
      <!-- <b-card
          :title=title
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem"
          class="mb-2"
        >
          <p>Author:xxxx</p>
          <p>Date: xx/xx/xxxx</p>
        </b-card> -->
      <b-card
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Card image"
        img-top
        img-height="auto"
      >
        <b-card-text :title="title">
          {{ title }}
        </b-card-text>

        <footer class="small text-muted" :author="author" :date="date">
          : {{ author }}
          <b-icon icon="clock"></b-icon> {{ date }}
        </footer>
      </b-card>
    </nuxt-link>
  </b-col>
</template>
<script>
export default {

  props: {
    title: {
      type: String,
      require: true,
    },
    author: {
      type: String,
      require: true,
    },
    date: {
      type: String,
      require: true,
    },
  },
};
</script>
