<template>
    <div class="bg-white w-64 h-screen"> <!--parent container for background styling-->
        <div class="border-b border-gray-400"> <!--logo-->
            <img class="px-8 py-8" src="@/assets/logo.png"/>
        </div>
        <div>
            <ul>
                <li class="navitem">
                    Home
                </li>

                <li class="navitem">
                    Browse Job
                    <ul>
                        <li class="subnavitem">by title</li>
                        <li class="subnavitem">by company</li>
                        <li class="subnavitem">by salary</li>
                    </ul>
                </li>

                <li class="navitem">
                    Post Job
                </li>

                <li class="navitem">
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
.navitem {
    @apply mb-8 px-8;
}
.subnavitem {
    @apply mb-8 px-16;
}
</style>
