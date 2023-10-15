<template>
  <div class="post-container py-8">
    <h3 class="text-3xl font-bold"><NuxtLink :to="`/posts/1`">Title of Post</NuxtLink></h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Feb 2, 2023</div>
      <div>&middot;</div>
      <div>Ely Bourland</div>
    </div>
    <div class="post-preview leading-relaxed mt-4">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores porro esse non, molestiae pariatur magni nobis illum aliquid itaque temporibus repellat totam rem dignissimos veritatis debitis numquam error aut exercitationem natus quos ipsam. Non incidunt est pariatur unde cupiditate aliquam, fugiat placeat quidem, itaque numquam, sit delectus assumenda! Dolorem, recusandae.
    </div>
    <div class="mt-4">
      <NuxtLink :to="`/posts/1`" class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2">Read More</NuxtLink>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>