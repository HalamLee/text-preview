<template>
  <div class="outer">
    <div class="inner-container">
      <div class="speaker"></div>
      <div class="screen">
        <div class="header"></div>
        <div class="contents">
          <div class="message">test</div>
        </div>
      </div>
      <div class="button"></div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
* {
  box-sizing: border-box;
}
.outer {
  width: 400px;
  height: 800px;
  border: 2px solid #959595;
  background-color: rgb(246, 242, 242);
  border-radius: 32px;
}

.inner-container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.speaker {
  width: 50px;
  height: 7px;
  background-color: #b3b2b2;
  border-radius: 3px;
  margin: 10px 0;
}

.screen {
  width: 90%;
  height: 85%;
  background-color: rgb(246, 242, 242);
  border: 2px solid #959595;
  border-radius: 20px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}

.header {
  width: 100%;
  height: 90px;
  background-color: rgb(230, 228, 228);
}

.contents {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 8px;
}

.message {
  width: 100%;
  height: fit-content;
  padding: 15px;
  background-color: #959595;
  border-radius: 10px;
}

.button {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 1px solid #959595;
  background-color: #fff;
}
</style>
