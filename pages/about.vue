<template>
  <b-container>
    <div class="mt-5">
      <b-row md="2">
        <b-col md="7">
          <div class="pt-5">
            <h1>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h1>
            <b-button class="mt-5" variant="outline-success">Register</b-button>
          </div>
        </b-col>
        <b-col md="5">
          <b-img
            src="https://cdn.pixabay.com/photo/2020/07/08/04/12/work-5382501__340.jpg"
            alt=""
            class="py-4"
            height="auto"
            max-width="100%"
            fluid-grow
          />
        </b-col>
      </b-row>
    </div>
      <detailMember name="A" position="ABC" img_src="https://cdn.pixabay.com/photo/2017/07/20/07/04/lion-2521451__340.png"/>
      <detailMember name="B" position="ABC" img_src="https://cdn.pixabay.com/photo/2013/07/13/13/42/tux-161406__340.png"/>
      <detailMember name="C" position="ABC" img_src="https://cdn.pixabay.com/photo/2012/05/07/01/54/owl-47526__340.png"/>
  </b-container>
</template>

<script>
export default {};
</script>

<style>
.details{
  margin-top: 50px;
}
</style>
