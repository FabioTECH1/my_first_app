<template>
  <ion-page>
    <slot />
  </ion-page>
</template>

<script lang="ts">
import { IonPage } from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "BaseLayout",
  props: [],
  components: {
    IonPage,
  },
});
</script>