<template>
  <b-container>
    <div>
      <b-row class="justify-content-md-center">
        <b-col col lg="1"></b-col>
        <b-col cols="14" md="auto">
          <b-card
            tag="article"
            style="padding: 40px 50px 60px 50px"
            class="mb-2 flex-center"
          >
          <h2 style="color:#28a745">Login</h2>
            <b-form @submit="onSubmit" @reset="onReset" v-if="show">
              <b-form-group
                id="input-group-1"
                label="Email address:"
                label-for="input-1"
              >
                <b-form-input
                  id="input-1"
                  v-model="form.email"
                  type="email"
                  placeholder="Enter email"
                  required
                ></b-form-input>
              </b-form-group>

              <b-form-group
                id="input-group-2"
                label="Your password:"
                label-for="input-2"
              >
                <b-form-input
                  type="password"
                  id="input-2"
                  v-model="form.password"
                  placeholder="Enter password"
                  required
                ></b-form-input>
              </b-form-group>
                <b-row >
                  <b-col>
                <a href=""><p>Forgot Password?</p></a>
                  </b-col>
                  <b-col>
                <b-button class="ml-5" type="submit" variant="success">Submit</b-button>
                  </b-col>
                </b-row>
            </b-form>
          </b-card>
        </b-col>
        <b-col col lg="1"></b-col>
      </b-row>

      <b-card class="mt-3" header="Form Data Result">
        <pre class="m-0">{{ form }}</pre>
      </b-card>
    </div></b-container
  >
</template>

<script>
export default {
  data() {
    return {
      form: {
        email: '',
        password: '',
      },
      show: true,
    };
  },
  methods: {
    onSubmit(event) {
      event.preventDefault();
      alert(JSON.stringify(this.form));
    },
    onReset(event) {
      event.preventDefault();
      // Reset our form values
      this.form.email = '';
      this.form.password = '';
      // Trick to reset/clear native browser form validation state
      this.show = false;
      this.$nextTick(() => {
        this.show = true;
      });
    },
  },
};
</script>
