

<template>
<div class="ctr">
   <Questions />
    <Results />
    <button type="button" class="reset-btn">Reset</button>
</div>
</template>

<script>
import Questions from './components/Questions.vue';
import Results from './components/Results.vue';

export default{
    name: "App",
    components: { Questions, Results }
}
</script>

<style scoped>

</style>
