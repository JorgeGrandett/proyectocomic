<template>
  <div>

  </div>
</template>

<script>
import axios from "axios";
export default {
    name: "peticiones-api",
    created() {
    axios.get("https://cors-anywhere.herokuapp.com/xkcd.com/info.0.json").then((result) => {
      console.log(result.data);
    })
  }
}
</script>

<style>

</style>