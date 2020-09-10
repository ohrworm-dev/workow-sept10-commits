<template>
  <div class="h-64 rounded shadow-md bg-gray-300"> <!-- parent div for background styling -->
      <div class="px-4 py-4"> <!-- Div 1/3, includes job title and company -->
          <div class="font-bold text-lg text-gray-700">
          Job Title <!--{{job.title}}-->
          </div>
          <div class="block text-gray-700">
          Company <!--{{job.company}}-->
          </div>
      </div>
      <div class="h-20 px-5 overflow-hidden hover:overflow-auto"> <!-- Div 2/3, includes description -->
        <p class="text-gray-600">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula.
        <!-- {{job.description}} -->
        </p>
      </div>
      <div class="flex justify-between space-x-4 px-4 py-8" > <!-- Div 3, includes two buttons -->
          <button class="px-4 py-4 flex-1 bg-gray-600 hover:bg-gray-700 text-white font-bold rounded-md">
          Apply Now
          </button>
          <button class=" flex-1 bg-transparent hover:bg-gray-500 text-gray-500 hover:text-white font-bold border-2 border-gray-500 hover:border-transparent rounded-md">
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
  // Function and listeners for the buttons in div 3?
  // Do I need props if I use the data property?
  props: {
  //     // How do I reference the job description? job.description?
  //     job: {
  //         type: Object as PropType<JobSearchRecommendation>
  }
})
</script>
