<template>
    <div>
        <navbar />
        <heroimage />
        <Content />
    </div>
</template>

<script>
import navbar from '../components/navbar';
import Heroimage from '../components/heroimage';
import Content from '../components/Content';

export default {
  components: {
    navbar,
    Heroimage,
    Content
    }
 }
</script>

<style>

</style>
