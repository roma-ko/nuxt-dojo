  <script setup >
  //variable must match with file name '[id].vue'
  const route = useRoute().params

  definePageMeta({
  layout:"products"
})
  </script>
<template>
  <div>
    <p>Product details for {{ route.id }}</p>
  </div>
</template>

