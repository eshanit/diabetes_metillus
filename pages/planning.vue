<script setup>
</script>
<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-buttons slot="start">
                    <ion-back-button></ion-back-button>
                </ion-buttons>
                <ion-title><span class="text-sky-600">Mentors</span></ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding">
            <ion-list>
                <ion-text color="warning">
                    <h2>Choose the mentor(s) you are going to:</h2>
                </ion-text>
            </ion-list>
            <ion-button color="success" router-link="/">add Mentor</ion-button>
            <ion-list>
                <ion-item>
                    <ion-label>Co-Mentor 1</ion-label>
                    <ion-checkbox slot="end"></ion-checkbox>
                </ion-item>
                <ion-item>
                    <ion-label>Co-Mentor 2</ion-label>
                    <ion-checkbox slot="end"></ion-checkbox>
                </ion-item>
                <ion-item>
                    <ion-label>Co-Mentor 3</ion-label>
                    <ion-checkbox slot="end"></ion-checkbox>
                </ion-item>
                <ion-item>
                    <ion-label>Co-Mentor 4</ion-label>
                    <ion-checkbox slot="end"></ion-checkbox>
                </ion-item>
                <ion-item>
                    <ion-label>Co-Mentor 5</ion-label>
                    <ion-checkbox slot="end"></ion-checkbox>
                </ion-item>
            </ion-list>
            <ion-button class="ion-float-right" router-link="/facility">next</ion-button>
         
        </ion-content>
    </ion-page>
</template>
<style>
ion-checkbox {
    --size: 32px;
    --background-checked: #6815ec;
}

ion-checkbox::part(container) {
    border-radius: 6px;
    border: 2px solid #6815ec;
}
</style>