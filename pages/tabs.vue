<template>
    <ion-page>
      <ion-content>
        <ion-tabs>
          <ion-router-outlet />
          <ion-tab-bar slot="bottom" class="customNav" >
            <ion-tab-button tab="tab1" href="/tabs/tab1" class="customNavItem" >
              <ion-icon :icon="ioniconsHome" />
              <ion-label>Home</ion-label>
            </ion-tab-button>
  
            <ion-tab-button tab="tab2" href="/tabs/tab2" class="customNavItem" >
              <ion-icon :icon="ioniconsApps" />
              <ion-label>Collection</ion-label>
            </ion-tab-button>
  
            <ion-tab-button tab="tab3" href="/tabs/tab3" class="customNavItem" >
              <ion-icon :icon="ioniconsHeart" />
              <ion-label>Likes</ion-label>
            </ion-tab-button>
  
            <ion-tab-button tab="tab4" href="/tabs/tab4" class="customNavItem" >
              <ion-icon :icon="ioniconsHelpCircle" />
              <ion-label>About</ion-label>
            </ion-tab-button>
          </ion-tab-bar>
        </ion-tabs>
      </ion-content>
    </ion-page>
</template>

<style scoped>

.customNav {
  background-color: #eee;
  padding: 1rem;
  border: none;
  border-top-right-radius: 2rem;
  border-top-left-radius: 2rem;
}
.customNavItem {
  background: none;
}

@media (prefers-color-scheme: dark) {
  .customNav {
    background-color: #4b4b4b;
  } 
}

</style>
  