<template>
    <ion-page>
        <ion-header :translucent="true" >
            <ion-toolbar>
                <ion-title>Home page</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content :fullscreen="true" >
            <ion-header collapse="condense" class="topHeadTool" >
                <ion-toolbar >
                    <ion-title>Welcome page</ion-title>
                </ion-toolbar>
            </ion-header>
            <div class="content">
                <h1>Caalee</h1>
                <p>Icon & logo wallpapers</p>
                <ion-img src="/images/welcomeImage.png" alt="caalee welcome image" ></ion-img>
                <ion-button 
                    class="custom-button"
                    style="--border-radius: 2rem; margin-top: 3rem;" 
                    router-link="/tabs/tab1" 
                >Get Started</ion-button>
            </div>
        </ion-content>
    </ion-page>
</template>

<style>
.topHeadTool {
    border: none;
    background: none;
}
.content {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 80%;
}
.content h1 {
    font-size: 4rem;
    font-weight: 800;
}
.custom-button {
    padding: 0;
}
</style>