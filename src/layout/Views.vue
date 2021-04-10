<template>
  <b-container fluid>
    <router-view :key="$route.path" />
  </b-container>
</template>

<script>
export default {
  name: "Views",
};
</script>
