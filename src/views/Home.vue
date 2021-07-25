<template>
  <section>
    <h1>View home</h1>
    <BaseButton variant="danger" text="Botão" to="/about"></BaseButton>
    <BaseInput placeholder="Digite algo" v-model="nome"></BaseInput>
    <BaseInput placeholder="Digite algo" v-model="idade"></BaseInput>
  </section>
</template>

<script>
import BaseButton from "../components/Buttons/BaseButton.vue";
import BaseInput from "../components/Input/BaseInput.vue";
export default {
  name: "Home",
  components: {
    BaseButton,
    BaseInput,
  },
  data() {
    return {
      nome: "Nome",
      idade: "Idade",
    };
  },
};
</script>
