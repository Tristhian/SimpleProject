<script setup>
import { ref } from 'vue';
import downloadImg from '../assets/images/download.jpeg';

const img = ref(downloadImg);
</script>

<template>
    <div class="flex items-center justify-center min-h-screen bg-blue-300 gap-4">
        <div class="bg-gray-200 shadow-lg rounded- p-9 w-96 ">
            <img :src="img" alt="A boy in orange jacket" class="rounded-full w-32 h-32 mx-auto border-gray-300">

            <div class="text-center">
                <label for="Fullname" class="text-xl mt-4 font-bold">Tristhian Bhong Geron</label>
                <p class="text-center mt-1">Hi, I am just A beginner in Vue.js!</p>

                <div class="flex space-x-3 justify-center">
                    <button class="bg-blue-300 text-white rounded py-2 px-5 mt-3 hover:bg-blue-500 ">Follow</button>

                    <button class=" bg-gray-400 text-white rounded py-2 px-4 mt-3
                    hover:bg-gray-700 ">Unfollow</button>
                </div>

            </div>


        </div>





    </div>

</template>