<template>
    <div class="bg-white w-64 h-screen"> <!--parent container for background styling-->
        <div class="border-b border-gray-400"> <!--logo-->
            <img class=" py-8" src="@/assets/logo.png"/>
        </div>

        <div >
            <ul class="px-8 flex-col items-stretch">
                <li>
                    Home
                </li>

                <li>
                    Browse Job
                    <ul class="px-16">
                        <li>by title</li>
                        <li>by company</li>
                        <li>by salary</li>
                    </ul>
                </li>

                <li>
                    Post Job
                </li>

                <li>
                    Help
                </li>
            </ul>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
})
</script>

<style>

</style>
