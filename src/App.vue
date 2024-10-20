<template>
  <div id="select">
    <label for="station">Bahnhof: </label>
    <input type="text" id="station">
    <button>ok</button>
  </div>

</template>

<script>

export default {
  name: 'app',
  components: {},
  data() {
    return {
      station: 'Altnau'
    }
  },
  methods: {},
}
</script>
