<template color="#445064">
  <v-container fluid class="text-xs-center">
    <v-layout justify-center :align-center="$vuetify.breakpoint.mdAndUp" fill-height>
      <v-flex xs12 md10>
        <h1 class="title my-5">About WATCH ONLINE WITHOUT DOWNLOADING</h1>

        <p>Live share and play media of torrent files online.</p>
        <p>
        Subtitles from
          <a href="https://opensubtitles.org">opensubtitles.org</a>.
        </p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "about",
  created() {
    document.title = "GomoviesLink - About";
  }
};
</script>
