<template>
  <div>
    <lv-input />
    <Calender />
  </div>
</template>

<script>
import Calender from "./components/Calender.vue";
import LvInput from "lightvue/input";
export default {
  components: { Calender, LvInput },
};
</script>

<style></style>
