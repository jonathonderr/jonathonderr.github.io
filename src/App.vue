<template>
  <v-app>
    <v-app-bar
      app
      color="white"
    >
      <v-row no-gutters align="center">
        <v-col cols="2">
          <v-row no-gutters align="center">
            <v-col cols="4">
              <v-img
                  alt="Avatar"
                  class="rounded"
                  height="50"
                  width="50"
                  src="https://avatars.githubusercontent.com/u/11656323?s=400&u=47f0363916b2a96d69507b6fdd55418a5ddd4b2a&v=4"
                />
            </v-col>
            <v-col cols="8">
              Jonathon Derr
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="10">
          <v-row no-gutters justify="end">
            <v-cols col="10">
              <v-tabs>
                <v-tab>Projects</v-tab>
                <v-tab>Education</v-tab>
                <v-tab>About Me</v-tab>
              </v-tabs>
            </v-cols>
          </v-row>
        </v-col>
      </v-row>
    </v-app-bar>

    <v-main>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
 .debug {
   background-color: red;
 }
</style>