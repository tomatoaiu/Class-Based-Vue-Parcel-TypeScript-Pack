<template>
  <div>
    {{ word }}
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

export default class App extends Vue {
  word: string = 'Hello world'
}
</script>
