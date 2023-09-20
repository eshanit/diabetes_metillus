<template>
    <ion-page>
        <ion-content :fullscreen="true">
            <div id="container">
                <!-- component -->
                <div class="flex min-h-screen items-center justify-center">
                    <div class="relative h-[800px] w-[400px] overflow-hidden rounded-3xl">
                        <!--div class="h-full w-full bg-[100%]"
                            style="background-image: url('https://img.freepik.com/free-vector/technology-background_23-2148119855.jpg?w=2000&t=st=1689179372~exp=1689179972~hmac=8a67af351443807b8728d4c2e1b067ba4a54be7b07c038cac30bdb71291062c1');">
                        </div-->
                        <div
                            class="absolute bottom-0 flex h-3/4 w-full flex-col rounded-t-3xl bg-white bg-opacity-20 shadow">
                            <form class="mt-10 space-y-8 px-10 py-10 text-center">
                                <div class="group relative">
                                    <input type="text" id="username" required
                                        class="peer h-14 w-full rounded-3xl bg-gray-100 px-4 text-sm outline-none" />
                                    <label for="username"
                                        class="absolute left-2 top-0 flex h-full transform items-center pl-2 text-base transition-all duration-300 group-focus-within:-top-7 group-focus-within:h-1/2 group-focus-within:pl-0 group-focus-within:text-base group-focus-within:text-white peer-valid:-top-7 peer-valid:h-1/2 peer-valid:pl-0 peer-valid:text-base peer-valid:text-white">Username</label>
                                </div>

                                <div class="group relative">
                                    <input type="text" id="password" required
                                        class="peer h-14 w-full rounded-3xl bg-gray-100 px-4 text-sm outline-none" />
                                    <label for="password"
                                        class="absolute left-2 top-0 flex h-full transform items-center pl-2 text-base transition-all duration-300 group-focus-within:-top-7 group-focus-within:h-1/2 group-focus-within:pl-0 group-focus-within:text-base group-focus-within:text-white peer-valid:-top-7 peer-valid:h-1/2 peer-valid:pl-0 peer-valid:text-base peer-valid:text-white">Password</label>
                                </div>

                                <ion-button router-link="/dashboard"
                                    class="h-12 w-1/2 rounded-3xl bg-slate-500 text-white transition-all duration-300 hover:bg-blue-800">Login</ion-button>

                                <a href="#" class="inline-flex !w-auto justify-center font-medium text-white">Forgot
                                    password?</a>
                            </form>

                            <p class="gap-2 text-center text-white">
                                Don't have an account?
                                <a href="#" class="font-semibold text-blue-900 hover:text-blue-800">Sign up</a>
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </ion-content>
    </ion-page>
</template>
  
<style scoped>
#container {
    text-align: center;

    position: absolute;
    left: 0;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
}

#container strong {
    font-size: 20px;
    line-height: 26px;
}

#container p {
    font-size: 16px;
    line-height: 22px;

    color: #8c8c8c;

    margin: 0;
}

#container a {
    text-decoration: none;
}
</style>