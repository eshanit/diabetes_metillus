<script setup>
</script>
<template>
    <ion-page>
        <ion-content>
            <ion-header>
                <ion-toolbar>
                    <ion-title size="small">Diabetes Metillus
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                        Introduction and Initial Evaluation
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                        Knowledge
                        <ion-icon :icon="ioniconsChevronForward"></ion-icon>
                        Question 1
                    </ion-title>
                </ion-toolbar>
            </ion-header>
            <div id="container">
                <ion-list :inset="true">
                    <ion-item-group>
                        <ion-item>
                            <ion-card class=" w-full">
                                <ion-card-header>
                                    <ion-card-title>Question</ion-card-title>
                                </ion-card-header>
                                <ion-card-content>
                                    <div class=" text-purple-500 text-lg"> Defines Diabetes Mellitus.</div>
                                </ion-card-content>
                            </ion-card>
                        </ion-item>

                        <ion-item>
                            <ion-card class=" w-full">
                                <ion-card-header>
                                    <ion-card-title>Answer Guide</ion-card-title>
                                </ion-card-header>
                                <ion-card-content>
                                    <div> A group of metabolic diseases characterized by hyperglycaemia resulting from
                                        defects in
                                        insulin secretion, insulin action or both.</div>
                                </ion-card-content>
                            </ion-card>
                        </ion-item>
                        <ion-item>
                            <ion-card class=" w-full">
                                <ion-card-header>
                                    <ion-card-title>Scoring Guide</ion-card-title>
                                </ion-card-header>
                                <ion-card-content>
                                    <ion-radio-group allow-empty-selection="true" value="turtles">
                                        <ion-radio aria-label="Medium" color="medium" value="0">Cannot be evaluated
                                        </ion-radio><br />
                                        <ion-radio aria-label="Danger" color="danger" value="cats"><span
                                                class="text-red-500">Gave wrong answer</span></ion-radio><br />
                                        <ion-radio aria-label="Warning" color="warning" value="turtles"><span
                                                class="text-orange-500">Partialy answered</span></ion-radio><br />
                                        <ion-radio aria-label="Success" color="success" value="fish"><span
                                                class="text-green-500">Answered correctly</span></ion-radio><br />
                                    </ion-radio-group>
                                </ion-card-content>
                            </ion-card>
                        </ion-item>
                    </ion-item-group>
                </ion-list>
            </div>

            <ion-button router-link="/">back</ion-button>
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
}</style>