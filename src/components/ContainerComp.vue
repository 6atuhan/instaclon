<template>

<recomm-comp></recomm-comp>
<stories-comp></stories-comp>

<div><PostsComp v-for="i in 5 " :key="i"></PostsComp></div>




</template>

<script setup>
import StoriesComp from './StoriesComp.vue';
import PostsComp from './PostsComp.vue';
import RecommComp from './RecommComp.vue';

</script>