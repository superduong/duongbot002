<template>
  <div class="home">
    <div class="container col-12 col-sm-6 col-lg-4">
      <bot-list />
    </div>
    <hr />
    <!-- <img alt="Freqtrade logo" src="../assets/freqtrade-logo.png" width="450px" class="my-5" /> -->
    <div title="Freqtrade logo" class="logo-svg my-5 mx-auto" />
    <div>
      <h1>Welcome Duong's Bot</h1>
    </div>
    <div>How to create a machine make auto dollar</div>
    <br />
    <p>
      If you need any help, please refer to the
      <a href="http://3.80.202.162:8080/">Tutorial</a>.
    </p>

    <p>Have fun - <i>wishes you become Billionaire</i></p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

import BotList from '@/components/BotList.vue';

export default defineComponent({
  name: 'Home',
  components: { BotList },
});
</script>

<style lang="scss" scoped>
.home {
  margin-top: 1.5em;
}
.logo-svg {
  -webkit-mask: url(../assets/freqtrade-logo-mask.png) no-repeat center;
  -webkit-mask-size: 240px 240px;
  mask: url(../assets/freqtrade-logo-mask.png) no-repeat center;
  mask-size: contain;
  width: 250px;
  height: 250px;
}
</style>
