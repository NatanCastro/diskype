<script setup lang="ts"></script>
<template>
  <div class="container">
    <img id="logo" src="/logo.svg" alt="" />
    <div id="profile"></div>
    <div id="chats">
      <h1>CHATS</h1>
      <nav></nav>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

#logo {
  width: 100%;
  height: 50px;
  background-color: #fe43ef33;
}

#profile {
  width: 100%;
  height: 250px;
  background-color: #ecf3;
}

#chats {
  flex: 1;
  background-color: #ea43;
}
</style>
