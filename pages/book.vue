<template>
  <div>
    <category />
    <hr />
    <div>
      <div>
        <b-row>
          <b-col>
            <partBook />
            <b-navbar>
              <b-collapse id="nav-collapse" is-nav>
                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                  <b-nav-form>
                    <b-form-input
                      class="mr-sm-2"
                      placeholder="Search"
                    ></b-form-input>
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
          </b-col>
        </b-row>
      </div>
      <div>
        <b-row>
          <bookPost/>
          <bookPost/>
          <bookPost/>
          <bookPost/>
        </b-row>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
