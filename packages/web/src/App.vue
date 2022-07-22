<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Http1 from './components/http1.vue'
import Http2 from './components/http2.vue'
import Sse from './components/sse.vue'
import WebRTC from './components/webRTC.vue'
import WebSocket from './components/webSocket.vue'
import WebTransport from './components/webTransport.vue'
</script>

<template>
  <div>
    <Http1 />
    <Http2 />
    <Sse />
    <WebRTC />
    <WebSocket />
    <WebTransport />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
