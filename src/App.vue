<template>
    <div id="app">
        <b-container>
            <b-jumbotron header="Calculator">
                <Calculator/>
            </b-jumbotron>
        </b-container>
    </div>
</template>

<script>
  import Calculator from './components/Calculator.vue';

  export default {
    name: 'app',
    components: {
      Calculator,
    },
  };
</script>

<style>
</style>
