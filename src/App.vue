<template>
  <div id="app">
    <div class="container" style="width:600px">
      <div class="my-4">
        <h3>bezkoder.com</h3>
        <h4>Vue.js upload Image with Preview</h4>
      </div>

      <upload-image></upload-image>
    </div>
  </div>
</template>

<script>
import UploadImage from "./components/UploadImage";

export default {
  name: "App",
  components: {
    UploadImage
  }
};
</script>
