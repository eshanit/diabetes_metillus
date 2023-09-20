<template>
    <ion-page>
        <ion-content :fullscreen="true">
            <div>This is the dash</div>
            <div class=" p-3 space-y-4 z-0">
                <h4 class="font-semibold mt-2">Category</h4>
                <div class="flex items-center justify-between overflow-y-scroll text-gray-500 cursor-pointer space-x-3">
                    <div
                        class="flex flex-col items-center justify-center w-1/2  h-20  bg-green-200 rounded-2xl text-green-600 shadow hover:shadow-md cursor-pointer mb-2 p-1 bg-white transition ease-in duration-300">
                        <a target="_blank" rel="noopener noreferrer" href="/planning">
                            <i class="far fa-hotel"></i>
                            <p class="text-sm mt-1">Evaluate</p>
                        </a>
                    </div>
                    <div
                        class="flex flex-col items-center justify-center w-1/2  h-20  bg-yellow-200 rounded-2xl text-yellow-600  shadow hover:shadow-md cursor-pointer mb-2 p-1 bg-white transition ease-in duration-300">
                        <i class="far fa-bus"></i>
                        <p class="text-sm mt-1">Facilities</p>
                    </div>

                    <div
                        class="flex flex-col items-center justify-center w-1/2  h-20  bg-indigo-200  rounded-2xl  text-indigo-500 shadow hover:shadow-md cursor-pointer mb-2 p-1 bg-white transition ease-in duration-300">
                        <i class="far fa-mountains"></i>
                        <p class="text-sm mt-1">Mentees</p>
                    </div>
                    <div
                        class="flex flex-col items-center justify-center w-1/2  h-20  bg-pink-200   rounded-2xl text-pink-500 shadow hover:shadow-md cursor-pointer mb-2 p-1 bg-white transition ease-in duration-300">
                        <i class="far fa-umbrella-beach"></i>
                        <p class="text-sm mt-1">Mentors</p>
                    </div>
                </div>
            </div>
        </ion-content>
    </ion-page>
</template>