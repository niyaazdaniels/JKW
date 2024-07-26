<template>
  <div class="sk-ww-instagram-reels" id="instagram" data-embed-id="25442104"></div>
</template>

<script>
export default {
  mounted() {
    const script = document.createElement("script");
    script.src = "https://widgets.sociablekit.com/instagram-reels/widget.js";
    script.async = true;
    script.defer = true;
    document.body.appendChild(script);
  },
};
</script>

<style scoped>
#instagram{
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 600px;
}
</style>
