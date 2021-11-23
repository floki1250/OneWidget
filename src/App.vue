<template>
  <div id="outer-circle">
    <div v-for="i in 5" :key="i">
      <div>
        <q-avatar size="60px" font-size="20px" color="teal" text-color="white"
          >A</q-avatar
        >
      </div>
    </div>
    <div id="inner-circle">
      <img
        src="../src/assets/logo.png"
        alt=""
        srcset=""
        width="100"
        height="100"
      />
    </div>
  </div>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
});
</script>
