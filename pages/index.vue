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
                <img class="backWelcomeImg" src="/images/lightWelcome.png" alt="welcome image" />
                <div class="tContent">
                    <div>
                        <h1>Caalee</h1>
                        <p>Icon & logo wallpapers</p>
                    </div>
                    <!-- <ion-img src="/images/lightWelcomeGif.gif" alt="caalee welcome image" ></ion-img> -->
                    <button class="custom-button" >
                        <ion-nav-link router-link="/tabs/tab1" >Get Started</ion-nav-link>
                    </button>
                </div>
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
    position: relative;
}
.backWelcomeImg {
    display: block;
    width: 100%;
    object-fit: cover;
    height: 100vh;
}
.tContent {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
}
.tContent div {
    text-align: center;
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
    /* margin-top: 3rem; */
    background-color: var(--primary);
    color: #ffffff;
    border-radius: 99px;
    font-weight: 800;
}

</style>