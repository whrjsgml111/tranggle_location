<template>
  <v-main>
    <v-container
      class="fill-height"
      fluid
    >
      <v-row
        align="center"
        justify="center"
      >
        <v-col
          cols="12"
          sm="8"
          md="4"
        >
          <v-card class="elevation-12">
            <v-toolbar
              color="primary"
              dark
              flat
              class="login_bg"
            >
              <v-toolbar-title>위치 관제 서비스</v-toolbar-title>
              <v-spacer></v-spacer>
            </v-toolbar>
            <v-card-text>
              <!-- <v-form @submit="login" onSubmit="return false;" method="post"> -->
              <v-form onSubmit="return false;" method="post">
                <v-text-field
                  label="아이디"
                  name="id"
                  prepend-icon="mdi-account"
                  type="text"
                ></v-text-field>
                <v-text-field
                  label="비밀번호"
                  name="password"
                  prepend-icon="mdi-lock"
                  type="password"
                ></v-text-field>
                <v-spacer></v-spacer>
                <v-btn type="submit" class="login_btn" color="primary">로그인</v-btn>
              </v-form>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-main>
</template>
<script>
export default {
  name: 'Login',
  data () {
    return {
    }
  },
  components: {
  },
  watch: {
  },
  computed: {
  },
  methods: {
  },
  mounted () {
  }
}
</script>
<style scoped>
  .login_btn {
    width:100%;
    background-color: #00838f !important;
  }
  .login_bg {
    background-color: #00838f !important;
  }
</style>
