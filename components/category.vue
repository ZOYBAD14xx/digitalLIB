<template>
      <div class="category">
      <p>Text</p>
      <b-row cols="1" cols-sm="2" cols-md="4" cols-lg="4">
        <b-col col lg="1"> Level </b-col>
        <b-col>
          <b-form-select class="select" v-model="selected" :options="options"></b-form-select>
        </b-col>
        <b-col col lg="1"> Category </b-col>
        <b-col>
          <b-form-select class="select" v-model="selected" :options="options"></b-form-select>
        </b-col>
      </b-row>
    </div>
</template>

<script>
export default {
  data() {
    return {
      selected: null,
      options: [
        { value: null, text: 'Please select an option' },
        { value: 'a', text: 'This is First option' },
        { value: 'b', text: 'Selected Option' },
        { value: 'd', text: 'This one is disabled' },
      ],
    };
  },
}
</script>

<style>
.select{
  box-shadow: none !important;
  outline: none !important;
  color:green;
}
</style>
