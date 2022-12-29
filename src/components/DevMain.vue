<template>
  <main class="content-wrap">
    <header class="content-head">
      <h1 class="is-blue">Take a test</h1>

      <div class="action">
        <button>Save search</button>
      </div>
    </header>

    <div class="content">
      <section class="info-boxes">
        <InfoBox />
        <InfoBox />
        <InfoBox />
        <InfoBox />
      </section>

      <section class="person-boxes">
        <PersonBox />
        <PersonBox />
        <PersonBox />
        <PersonBox />
        <PersonBox />
        <PersonBox />
        <PersonBox />
        <PersonBox />
      </section>
    </div>
  </main>
</template>

<script>
import PersonBox from "./PersonBox.vue";
import InfoBox from "./InfoBox.vue";

export default {
  name: "DevMain",
  components: { PersonBox, InfoBox },

  props: {},
};
</script>
