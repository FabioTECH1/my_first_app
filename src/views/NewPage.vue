<template>
  <base-layout>
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-back-button default-href="/home"></ion-back-button>
        </ion-buttons>
        <ion-title><h3>A new Page Heading</h3></ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content>
      <ion-toolbar>
        <form class="ion-padding" @submit.prevent="">
        <ion-list>
          <ion-item>
            <ion-label position="floating">Title</ion-label>
            <ion-input type="text" required/>
          </ion-item>
          <ion-item>
            <ion-label position="floating">Description</ion-label>
            <ion-textarea rows="4"></ion-textarea>
          </ion-item>
        </ion-list>
        <ion-button expand="full">Full Button</ion-button>
        </form>
        <ion-button expand="full" fill="outline">Ouline Button</ion-button>
        <ion-button expand="block" fill="outline">Block Ouline Button</ion-button>
      </ion-toolbar>
    </ion-content>
  </base-layout>
</template>


<script lang="ts">
import {
  IonLabel,
  IonInput,
  IonContent,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonImg,
  IonList,
  IonItem,
  IonButtons,
  IonButton,
  IonBackButton,
IonTextarea,
} from "@ionic/vue";

import { defineComponent } from "vue";

export default defineComponent({
  name: "NewPage",
  components: {
    IonLabel,
    IonInput,
    IonContent,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonImg,
    IonList,
    IonItem,
    IonButtons,
    IonButton,
    IonBackButton,
    IonTextarea
},
});
</script>
