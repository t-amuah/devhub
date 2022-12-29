<template>
  <div class="dashboard">
    <UserHeader />
    <DevAside />
    <div class="scroll">
      <DevMain />
    </div>
  </div>
</template>

<script>
import DevAside from "./components/DevAside.vue";
import UserHeader from "./components/UserHeader.vue";
import DevMain from "./components/DevMain.vue";

export default {
  name: "App",
  components: {
    UserHeader,
    DevAside,
    DevMain,
  },
};
</script>
