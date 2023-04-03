<template>
  <div>
  <Post :name="name" :date="date" :content="content" :likes="likes" :ref="ref"/>
  <Post :name="name" :date="date" :content="content" :likes="likes" :ref="ref"/>
  <Post :name="name" :date="date" :content="content" :likes="likes" :ref="ref"/>
</div>
</template>

<script>
import Post from './Post.vue'
export default {
 name:'',
 components:{
  Post,
 },
 props:{
  name: String,
  likes: Number,
  date: Number,
  content: String,
  filter: String,
 }
}
</script>

<style>

</style>