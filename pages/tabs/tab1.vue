<template>
    <ion-page>
      <ion-header>
        <ion-toolbar>
          <ion-title>Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <div class="container">
            <ion-text>Tab 1 content</ion-text>
            <ion-button router-link="/">Go Home</ion-button>
        </div>
      </ion-content>
    </ion-page>
  </template>

<style>

.container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 90%;
}

</style>
  