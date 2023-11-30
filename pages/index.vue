<template>
    <ion-page>
        <ion-header :translucent="true" >
            <ion-toolbar>
                <ion-title>Home page</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content :fullscreen="true" >
            <ion-header collapse="condense" >
                <ion-toolbar>
                    <ion-title size="large" >Home page</ion-title>
                </ion-toolbar>
            </ion-header>
            <div class="content">
                <p>Welcome to nuxt ionic</p>
                <ion-button router-link="/resources" >Get resources</ion-button>
            </div>
        </ion-content>

    </ion-page>
</template>

<style>

.content {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 80%;
}

</style>