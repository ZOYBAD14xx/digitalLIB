<template>
  <b-container>
    <topPageMain />
    <div class="main_content my-5">
      <b-row>
        <b-col sm="8">
          <p style="color: green">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
          </p>
          <h3>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti
            architecto amet.
          </h3>
          <div>
            <b-row class="flex justify-content-between">
              <b-col>
                <p>author:</p>
              </b-col>
              <b-col>
                <p>date</p>
              </b-col>
            </b-row>
          </div>
          <hr />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam quia
            odio earum minus aliquam, deleniti doloremque id laboriosam! Dolores
            in pariatur, officia eum reiciendis earum ducimus voluptatibus
            obcaecati? Quas, alias. Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Quibusdam culpa suscipit laudantium voluptatum,
            sint, reprehenderit tempore magni earum eveniet harum eaque
            accusamus? Quasi itaque sit necessitatibus mollitia, alias id
            eligendi! Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Commodi ipsam eum sequi illum ducimus quia quasi, ad aspernatur.
            Asperiores ut quia doloremque porro modi laborum odit quae molestias
            rerum amet! Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Perferendis at alias minima eaque quisquam, nostrum iure eveniet
            ullam aliquam. Nam accusamus ab sit dolorum, consequuntur possimus
            repudiandae earum quis. Cumque. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Ipsam quia odio earum minus aliquam,
            deleniti doloremque id laboriosam! Dolores in pariatur, officia eum
            reiciendis earum ducimus voluptatibus obcaecati? Quas, alias. Lorem
            ipsum dolor sit amet consectetur adipisicing elit. Quibusdam culpa
            suscipit laudantium voluptatum, sint, reprehenderit tempore magni
            earum eveniet harum eaque accusamus? Quasi itaque sit necessitatibus
            mollitia, alias id eligendi! Lorem ipsum dolor sit amet, consectetur
            adipisicing elit.
          </p>
          <h3 style="color: green">Title</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam quia
            odio earum minus aliquam, deleniti doloremque id laboriosam! Dolores
            in pariatur, officia eum reiciendis earum ducimus voluptatibus
            obcaecati? Quas, alias. Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Quibusdam culpa suscipit laudantium voluptatum,
            sint, reprehenderit tempore magni earum eveniet harum eaque
            accusamus? Quasi itaque sit necessitatibus mollitia, alias id
            eligendi! Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Commodi ipsam eum sequi illum ducimus quia quasi, ad aspernatur.
            Asperiores ut quia doloremque porro modi laborum odit quae molestias
            rerum amet! Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Perferendis at alias minima eaque quisquam, nostrum iure eveniet
            ullam aliquam. Nam accusamus ab sit dolorum, consequuntur possimus
            repudiandae earum quis. Cumque. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Ipsam quia odio earum minus aliquam,
            deleniti doloremque id laboriosam! Dolores in pariatur, officia eum
            reiciendis earum ducimus voluptatibus obcaecati? Quas, alias. Lorem
            ipsum dolor sit amet consectetur adipisicing elit. Quibusdam culpa
            suscipit laudantium voluptatum, sint, reprehenderit tempore magni
            earum eveniet harum eaque accusamus? Quasi itaque sit necessitatibus
            mollitia, alias id eligendi! Lorem ipsum dolor sit amet, consectetur
            adipisicing elit. Commodi ipsam eum sequi illum ducimus quia quasi,
            ad aspernatur. Asperiores ut quia doloremque porro modi laborum odit
            quae molestias rerum amet! Lorem ipsum dolor sit amet consectetur
            adipisicing elit.
          </p>
        </b-col>

        <!-- right side-->
        <b-col sm="4">
          <div>
            <div>
              <b-row md="1">
                <b-col>
                  <h4>Search:</h4>
                </b-col>
              </b-row>
              <b-row>
                <b-col>
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
                </b-col>
              </b-row>
            </div>
            <div class="ml-3">
              <b-row>
                <sideCard />
                <sideCard />
                <sideCard />
                <sideCard />
              </b-row>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
  </b-container>
</template>
<script>
export default {
  layout: 'default',
};
</script>
