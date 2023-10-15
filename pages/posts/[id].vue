<template>
  <div class="container mx-auto w-1/2 py-8">
    <Title>{{ $route.params.id }} | {{ title }}</Title>
    <h3 class="text-3xl font-bold"><NuxtLink :to="`/posts/1`">Title of Post</NuxtLink></h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Feb 2, 2023</div>
      <div>&middot;</div>
      <div>Ely Bourland</div>
    </div>
    <div class="post-content mt-4">
      {{ $route.params.id }}Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe, eius dolores praesentium rem doloribus voluptas nisi reprehenderit sed officiis ab asperiores, voluptate id sint doloremque? Voluptatibus unde odit nihil praesentium? Cum, repudiandae pariatur similique quidem nam harum officiis ipsa perferendis esse facere unde quis sed nesciunt, soluta nemo nobis debitis praesentium! Facilis corrupti reprehenderit harum molestias cum perspiciatis cumque repellat omnis rem nesciunt est nulla voluptates veritatis eligendi iusto, ipsa soluta excepturi repellendus quidem aliquam saepe ducimus, adipisci quaerat? Harum iure excepturi velit aperiam quae sit fuga, voluptatem atque fugiat dolorum ipsa aliquid asperiores quaerat. Praesentium nesciunt iste labore veritatis.
  </div>
    </div>
</template>

<script setup>
  const title = useState('title')
</script>

<style scoped>

</style>