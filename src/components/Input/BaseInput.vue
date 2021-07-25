<template>
  <b-form-input
    :value="value"
    @input="$emit('input', $event.target.value)"
    :placeholder="placeholder"
  ></b-form-input>
</template>

<script>
export default {
  name: "BaseForm",

  props: {
    placeholder: {
      type: String,
    },

    value: {
      type: String,
    },
  },
};
</script>
