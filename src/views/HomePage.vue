<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title><h3>This a header title</h3></ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content>
      <ion-toolbar>
        <ion-list>
          <ion-item router-link="/newpage"
            >This is a list item linked to another page
          </ion-item>
          <ion-item>This is another list item</ion-item>
        </ion-list>
        <ion-img
          :src="'https://cdn.pixabay.com/photo/2016/07/29/14/33/ballet-1553359__340.jpg'"
        ></ion-img>
      </ion-toolbar>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonHeader,
  IonContent,
  IonTitle,
  IonToolbar,
  IonPage,
  IonImg,
  IonList,
  IonItem,
} from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomePage",
  props: [],
  components: {
    IonPage,
    IonContent,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonImg,
    IonList,
    IonItem,
  },
});
</script>

