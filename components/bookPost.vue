<template>
  <b-container class="py-2">
    <nuxt-link to="#" style="text-decoration: none; color: inherit">
    <b-card
      img-src="https://cdn.pixabay.com/photo/2015/11/19/21/10/glasses-1052010_960_720.jpg"
      img-height="200px"
      img-alt="Card image"
      img-left
      class="mb-3"
    >
      <h3>Title</h3>
      <b-card-text>
        {{ msg.slice(0,200)+"..." }}
      </b-card-text>
    </b-card>
    </nuxt-link>
    <hr>
    </b-container
  >
</template>
<script>
export default {
  data() {
    return {
      msg: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quae nisi explicabo, assumenda totam fugit velit quod. Nostrum, beatae libero. Distinctio corporis, commodi laborum sed necessitatibus totam asperiores blanditiis quidem iusto.",
    };
  },
};
</script>
