<template>
  <div class="card">
      <h2> {{ titulo }} </h2>
      <slot></slot>
      <p> {{ descricao }} </p>
  </div>
</template>

<script>
export default {
    name: 'EventCard',
    props: {
        titulo: String,
        icone: String,
        descricao: String,
    }

}
</script>

<style lang="scss" scoped>

$informaticaBlue: #1935A1;

    .card {
        width: 33%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        padding: 15px 20px;

        h2 {
            color: $informaticaBlue;
        }

        i {
            font-size: 30px;
        }
    }

</style>