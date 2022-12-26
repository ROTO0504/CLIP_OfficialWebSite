<template>
  <v-card
    elevation="2"
    shaped
  >
    <v-card-title class="text-h6">
      TeaserPV
    </v-card-title>

    <div style="padding:50% 0 0 0;position:relative;">
      <iframe
        src="https://player.vimeo.com/video/782086165?h=5d7d8d5007&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"
        allow="autoplay;
              fullscreen; picture-in-picture"
        allowfullscreen
        style="position:absolute;top:0;left:0;width:100%;height:100%;"
        frameborder="0"
        title="TeaserPV"
      />
    </div>
  </v-card>
</template>

<script>
export default {
  name: 'InspirePage'
}
