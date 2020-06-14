<template>
  <v-layout
    column
    justify-center
    align-center
  >
  <v-card-text>
      <v-row align="center" v-touch:swipe.left="() => alert(11)"> 
        <!-- v-touch:swipe.left="() => alert(11)" -->
        <v-checkbox
          v-model="includeFiles"
          hide-details
          class="shrink mr-2 mt-0"
        ></v-checkbox>
        aaaaaa
        <v-text-field label="New Task"></v-text-field>
      </v-row>
    </v-card-text>
  </v-layout>
</template>

<script>
import Vue from 'vue'
import Vue2TouchEvents from 'vue2-touch-events'
 
Vue.use(Vue2TouchEvents)

export default {
  components: {}
}
</script>
