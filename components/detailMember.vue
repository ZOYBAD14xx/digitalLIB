<template>
  <b-row cols="1" cols-sm="2" cols-md="4" cols-lg="2" class="mt-5">
    <b-col>
      <b-img
        :src="img_src"
        fluid
      ></b-img>
    </b-col>
    <b-col>
      <h4 :name="name">{{ name }}</h4>
      <h5 :position="position">{{ position }}</h5>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni alias,
        facere harum fugiat soluta veniam quae quod quisquam aliquid dicta
        consequatur, necessitatibus exercitationem qui natus. Sunt doloremque
        ipsum recusandae sint!
      </p>
    </b-col>
  </b-row>
</template>

<script>
export default {
  data(){
return {

      }
  },
  props:{
    name:{
      type:String,
      require:true
    },
    position:{
      type:String,
      require:true
    },
    img_src:{
      type:String,
      require:true
    },
  }

}
</script>

<style></style>
