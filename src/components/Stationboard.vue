<template>
  <div class="table-fixed-head">

  </div>
</template>

<script>
export default {
  name: "Stationboard",
  data() {
    return { };
  },
  mounted() {
  },

  props: { },
  methods: { },
};
</script>


<style scoped>
.table-fixed-head {
    position: fixed;
    top:0vh;
    left:0;
    width: 100vw;
    max-height: 100vh;
    overflow-y: scroll;
}
@media screen and (min-width: 40rem) {
    .table-fixed-head {
        top:10vh;
        left:10vw;
        width: 80vw;
        max-height: 80vh;
    }
    #select {
        display:block;
    }
}

table {
    width: 100%;
    table-layout: fixed;
    background-color: blue;
    opacity: 80%;
    backdrop-filter: blur(10px);
    border-collapse: collapse;
}
thead th,
caption {
    position: sticky;
    background-color: blue;
    border: 3px solid white;
}
caption {
    top:0;
}
thead th {
    top:70px;
}
tbody {
    overflow-y: scroll;
}
th,td {
    border:3px solid white;
    padding: 10px;
}

</style>