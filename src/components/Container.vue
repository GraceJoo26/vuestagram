<template>
  <div>
  <Post v-for ="(a,i) in 게시물" :key="a" :게시물="게시물[i]"/>
</div>
</template>

<script>
import Post from '@/components/Post.vue'
export default {
 name:'',
 components:{
  Post,
 },
 props:{
  게시물 : Array,
 }
}
</script>

<style>

</style>