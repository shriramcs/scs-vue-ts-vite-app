<script setup lang="ts">
</script>

<template>
  <div class="">
    <div class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 text-blue-200 p-5">
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
    </div>

    <div class="col-12 bg-gradient-to-r from-blue-100 via-purple-200 to-indigo-200 h-screen p-2">
        <router-view />
    </div>
  </div>
</template>
