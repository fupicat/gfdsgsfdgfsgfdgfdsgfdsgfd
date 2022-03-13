<template>
  <div>
    <Introducao :texto="contagem" />
    <button @click="adicionarUm()">adicionar um</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      contagem: 0,
    };
  },
  methods: {
    adicionarUm() {
      this.contagem += 1;
    },
  },
};
</script>

<style></style>
