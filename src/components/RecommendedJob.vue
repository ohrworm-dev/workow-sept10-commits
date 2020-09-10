<template>

<div class="max-w-sm rounded overflow-hidden shadow-lg"> <!-- parent div for background styling and allignment -->

    <div class="px-6 py-4"> <!-- Div 1, includes job title and company -->
        <div class="font-bold text-xl mb-2">job title</div>
        <div class="font-bold text-xl mb-2">company</div>
    </div>

    <div class="  px-6 py-4"> <!-- Div 2, includes job description -->
        <p class="text-gray-700 text-base">
        {{ job.description }}
        </p>
    </div>

    <div class=""> <!-- Div 3, includes two buttons -->
        <button class="bg-gray-600 hover:bg-gray-700 text-white py-2 px-4 rounded">
        Apply Now
        </button>
        <button class="bg-transparent hover:bg-gray-500 text-gray-700 hover:text-white py-2 px-4 border border-gray-600 hover:border-transparent rounded">
        Save
        </button>
  </div>
</div>
</template>

<script lang="ts">
import Vue from 'vue'
// import { JobSearchRecommendation } from '~/types/types'

export default Vue.extend({
  // Do I need data if the component has no created data, and only uses inherited data, such as job.description in this case?

  // Do I need props if I have data?
  // props: {
  //     // How do I reference the job description? job.description?
  //     job: {
  //         type: Object as PropType<JobSearchRecommendation>
  // }
})
</script>
