<script setup>
</script>
<template>
    <ion-page>

        <ion-header>
            <ion-toolbar>
                <ion-buttons slot="start">
                    <ion-back-button></ion-back-button>
                </ion-buttons>
                <ion-title><span class="text-sky-600">Mentees</span></ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding">
            <ion-list>
                <ion-list>
                    <ion-text color="warning">
                        <h2>Choose the Mentee you are going to evaluate:</h2>
                    </ion-text>
                </ion-list>
                <ion-item>
                    <ion-label>Mentee 1</ion-label>
                    <ion-button slot="end" router-link="/dm/iie/knowledge/Q1">Go
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                    </ion-button>
                </ion-item>
                <ion-item>
                    <ion-label>Mentee 2</ion-label>
                    <ion-button slot="end">Go
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                    </ion-button>
                </ion-item>
                <ion-item>
                    <ion-label>Mentee 3</ion-label>
                    <ion-button slot="end">Go
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                    </ion-button>
                </ion-item>
                <ion-item>
                    <ion-label>Mentee 4</ion-label>
                    <ion-button slot="end">Go
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                    </ion-button>
                </ion-item>
                <ion-item>
                    <ion-label>Mentee 5</ion-label>
                    <ion-button slot="end">Go
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                    </ion-button>
                </ion-item>
            </ion-list>
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