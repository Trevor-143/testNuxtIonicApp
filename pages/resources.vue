<template>
    <ion-page>
        <ion-header :translucent="true" >
            <ion-toolbar>
                <ion-title>Resource page</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content :fullscreen="true" >
            <ion-header collapse="condense" >
                <ion-toolbar>
                    <ion-title size="large" >Resource page</ion-title>
                </ion-toolbar>
            </ion-header>
        </ion-content>

        <div class="content">
            <ion-button router-link="/" >Go home</ion-button>
        </div>

    </ion-page>
</template>
