<template>
<div class="container">
  <div class="max-h-1/5 rounded shadow-md bg-gray-300"> <!-- parent div for background styling and allignment -->
      <div class="w-full px-4 py-4"> <!-- Div 1, includes job title and company -->
          <div class="block font-bold text-lg text-gray-800">Job Title</div>
          <div class="block text-gray-700">Company</div>
      </div>
      <div class='overflow-y-auto'>
        <p class=" px-5 py-4 text-gray-600 text-base overflow-y-auto">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla blandit rutrum mollis. In hac habitasse platea dictumst. Ut risus metus, aliquet quis cursus in, blandit id neque. Proin ornare tortor et finibus eleifend. Cras ornare sed velit in egestas. Suspendisse sed massa tincidunt, dictum sapien posuere, iaculis purus. Pellentesque efficitur sed urna eu condimentum. Donec eget ex maximus, posuere ligula eu, sollicitudin quam. Etiam eu orci ligula.
        </p>
      </div>
      <div class="flex justify-between space-x-2 px-4 py-4"> <!-- Div 3, includes two buttons -->
          <button class="w-1/2 py-3 bg-gray-600 hover:bg-gray-700 text-white font-bold rounded-md">
          Apply Now
          </button>
          <button class=" w-1/2 bg-transparent hover:bg-gray-500 text-gray-600 font-bold hover:text-white border-2 border-gray-600 hover:border-transparent rounded-md">
          Save
          </button>
    </div>
  </div>
</div>
</template>

<script lang="ts">
import Vue from 'vue'
// import { JobSearchRecommendation } from '~/types/types'

export default Vue.extend({
  // Do I need data if the component has no created data, and only uses inherited data, such as job.description in this case?

  // Do I need props if I have data?
  props: {
  //     // How do I reference the job description? job.description?
  //     job: {
  //         type: Object as PropType<JobSearchRecommendation>
  }
})
</script>
