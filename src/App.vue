<template>
  <v-app>
    <div id="app">
      <v-toolbar dark>
        <v-toolbar-title><v-icon class="mr-2">playlist_add_check</v-icon>VUE TODO</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn flat><v-icon class="mr-2">account_box</v-icon>Register</v-btn>
          <v-btn flat><v-icon class="mr-2">fingerprint</v-icon>Login</v-btn>
          <v-btn flat><v-icon class="mr-2">exit_to_app</v-icon>Logout</v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </div>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Work Sans", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
