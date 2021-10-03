<template>
  <b-container>
    <div>
      <h4>Popular :</h4>
      <b-row class="py-2">
          <blogCard title="Blog 1" author="Noname" date="21/02/2021" />
            <blogCard title="Blog 2" author="Noname" date="3/06/2021"/>
            <blogCard title="Blog 3" author="Noname" date="4/07/2021"/>
            <blogCard title="Blog 4" author="Noname" date="1/09/2021"/>
      </b-row>
      <div class="spacer"></div>
      <b-navbar toggleable="lg" type="light" variant="light">
        <h4>All blogs :</h4>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-nav-form>
              <b-form-input class="mr-sm-2" placeholder="Search"></b-form-input>
              <b-button
                variant="outline-success"
                class="my-2 my-sm-0"
                type="submit"
                >Search</b-button
              >
            </b-nav-form>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
      <b-row class="py-2">
        <blogCard title="Blog 1" />
        <blogCard title="Blog 2" />
        <blogCard title="Blog 3" />
        <blogCard title="Blog 4" />
      </b-row>
    </div>
  </b-container>
</template>

<script>
export default {};
</script>

<style>
.spacer {
  margin-top: 10px;
}
</style>
