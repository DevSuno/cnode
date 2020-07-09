<template>
  <div id="app">
    <Header />
      <div class="main">
          <PostList />

      </div>
  </div>
</template>

<script>

import Header from "./components/Header";
import PostList from "./components/PostList";

export default {
  name: 'App',
  components: {
      PostList,
      Header,

  }
}
</script>

<style>
    .main{
        width: 80%;
        margin: 0 auto;
    }
</style>
