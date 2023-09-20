<script setup>
</script>
<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-buttons slot="start">
                    <ion-back-button></ion-back-button>
                </ion-buttons>
                <ion-title><span class="text-sky-600">Facilities</span></ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding">
            <ion-list>
                <ion-text color="warning">
                    <h2>Choose the facility you are going to:</h2>
                </ion-text>
            </ion-list>
            <ion-button color="success" router-link="/">add facility</ion-button>
            <ion-item>
                <ion-label>Facility 1</ion-label>
                <ion-button router-link="/mentees" slot="end">Mentees</ion-button>
            </ion-item>
            <ion-item>
                <ion-label>Facility 2</ion-label>
                <ion-button slot="end">Mentees</ion-button>
            </ion-item>
            <ion-item>
                <ion-label>Facility 3</ion-label>
                <ion-button slot="end">Mentees</ion-button>
            </ion-item>
            <ion-item>
                <ion-label>Facility 4</ion-label>
                <ion-button slot="end">Mentees</ion-button>
            </ion-item>
            <ion-item>
                <ion-label>Facility 5</ion-label>
                <ion-button slot="end">Mentees</ion-button>
            </ion-item>
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