<template>
    <Layout>
        <section class="max-w-7xl mx-auto px-4">
            <div class="bg-gray-900 px-28 py-28 rounded-t-3xl bg-cover bg-right bg-no-repeat"
                 style="background-image: url('/img/HeroImagelg.png')">
                <Logo class="w-72 text-white"/>

                <p class="mt-3 text-xl text-white">
                    Get to know more about your cat breed
                </p>

                <div class="relative mt-12 w-96">
                    <input type="text"
                           class="w-full pl-7 pr-14 py-5 leading-7 bg-white text-gray-800 focus:outline-none placeholder-gray-900 rounded-full"
                           placeholder="Enter your breed">
                    <span class="absolute inset-y-0 right-6 flex justify-center items-center">
                        <svg class="w-4 h-4 text-gray-900 " xmlns="http://www.w3.org/2000/svg" fill="none"
                             viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
        d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/>
</svg>
                    </span>
                </div>
            </div>

            <div class="pt-10 pb-24 px-28 bg-gray-200 rounded-b-3xl">
                <p>Most Searched Breeds</p>
                <span class="mt-2 block w-14 h-1 bg-gray-900"></span>

                <div class="mt-9 flex justify-between items-end">
                    <h2 class="font-black text-5xl w-1/2">66+ Breeds For you to discover</h2>
                    <a href="" class="inline-flex items-center space-x-2 mt-10 font-semibold uppercase">
                        <span>See more</span>
                        <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
                        </svg>
                    </a>
                </div>

                <div class="mt-8 grid grid-cols-4 gap-12">
                    <div>
                        <img src="" alt="cat image">
                        <p class="font-semibold">Bengal</p>
                    </div>

                    <div>
                        <img src="" alt="cat image">
                        <p>Savannah</p>
                    </div>

                    <div>
                        <img src="" alt="cat image">
                        <p>Norwegian Forest Cat</p>
                    </div>

                    <div>
                        <img src="" alt="cat image">
                        <p>Selkirk Rex</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="max-w-7xl mx-auto px-4">
            <div class="px-28 py-24">
                <div class="flex items-center">
                    <div class="w-1/2 pr-10">
                        <span class="block w-16 h-1 bg-gray-900"></span>

                        <h3 class="mt-4 font-black text-5xl text-gray-900">Why should you have a cat?</h3>

                        <p class="mt-10 text-gray-900">
                            Having a cat around tou can actually
                            trigger the release of calming chemicals in
                            your body which lower your stress and
                            anxiety levels
                        </p>

                        <a href="" class="inline-flex items-center space-x-2 mt-10 font-semibold uppercase">
                            <span>Read more</span>
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
                            </svg>
                        </a>
                    </div>

                    <div class="">
                        <div class="grid grid-cols-2 gap-6">
                            <div class=""><img src="/img/image2.png" class="w-72" alt=""></div>
                            <div class="row-span-2"><img src="/img/image3.png" class="w-60" alt=""></div>
                            <div class="ml-auto"><img src="/img/image1.png" class="w-48" alt=""></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </Layout>
</template>

<script>
import Layout from "../Layouts/AppLayout";
import Logo from "../Components/Logo";

export default {
    name: "Home",
    components: {
        Layout,
        Logo
    }
}
</script>

<style scoped>

</style>
