<template>
  <b-button :variant="variant" :text="text" :type="type" :to="to">{{
    text
  }}</b-button>
</template>

<script>
export default {
  name: "PrimaryButton",

  props: {
    variant: {
      type: String,
    },

    text: {
      type: String,
    },

    type: {
      type: String,
    },

    to: {
      type: String,
    },
  },
};
</script>
