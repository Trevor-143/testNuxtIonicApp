<template>
    <ion-page>
        <!-- <ion-header :translucent="true" >
            <ion-toolbar>
                <ion-title>Home page</ion-title>
            </ion-toolbar>
        </ion-header> -->

        <ion-content :fullscreen="true" >
            <!-- <ion-header collapse="condense" class="topHeadTool" >
                <ion-toolbar >
                    <ion-title>Welcome page</ion-title>
                </ion-toolbar>
            </ion-header> -->
            <div class="content">
                <h1>Caalee</h1>
                <p>Icon & logo wallpapers</p>
                <ion-img src="/images/lightWelcomeGif.gif" alt="caalee welcome image" ></ion-img>
                <button class="custom-button" >
                    <ion-nav-link router-link="/tabs/tab1" >Get Started</ion-nav-link>
                </button>
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
    height: 100%;
}
.content h1 {
    font-size: 4rem;
    font-weight: 800;
}
.content p {
    margin-bottom: 2rem;
    margin-top: -1rem;
}
.custom-button {
    padding: 1.5rem 1rem;
    width: 70%;
    font-size: 1.5rem;
    margin-top: 3rem;
    background-color: var(--primary);
    color: #ffffff;
    border-radius: 99px;
    font-weight: 800;
}

</style>