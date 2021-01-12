<template>
  <div id="app">
    <container>
      <ChatWindow>
        <ChatMessage v-bind:username="'Ivan'" v-bind:time="'21.12.2019 05:00:50'">Hello, World!!!</ChatMessage>
      </ChatWindow>
    </container>
  </div>
</template>

<script>
import container from './components/Container.vue'
import ChatMessage from './components/ChatMessage.vue'
import ChatWindow from './components/ChatWindow.vue'


export default {
  name: 'App',
  components: {
    container,
    ChatMessage,
    ChatWindow,
  }
}
</script>

<style>
  body {
    margin: 0;
    background-color: #f9f9fa;
  }
</style>
