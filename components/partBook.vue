<template>
  <b-breadcrumb :items="items"></b-breadcrumb>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          text: 'Bacherlor',
          href: '#',
        },
        {
          text: 'Database',
          active: true,
        },
      ],
    };
  },
};
</script>

<style></style>
