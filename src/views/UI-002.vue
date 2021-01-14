<template>
  <div class="test">
    <div class="errorMsgContainer">
      <div class="errorMsg">
        <span>Could not find the page you were looking for</span>
      </div>
      <button type="submit" class="errorButton">Go back</button>
    </div>
    <div class="rightMessage">
      <div class="number">404</div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.test {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  color: white;
  align-items: center;
  text-shadow: 1px black;
  height: 100vh;
  animation: 1000ms ease-in-out infinite seizure-mode;
}
.rightMessage {
  display: flex;
  flex-direction: column;
}
.number {
  font-size: 514px;
}
.sad {
  font-size: 192px;
}
span {
  font-size: 32px;
}
.errorMsgContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.errorButton {
  margin-top: 10px;
  background-color: white;
  border: none;
  color: lightgrey;
  padding: 5px;
  text-align: center;
  text-decoration: none;
  font-size: 32px;
  width: 50%;
}

@keyframes color-change {
  0% {
    color: teal;
  }
  20% {
    color: gold;
  }
  40% {
    color: indianred;
  }
  60% {
    color: violet;
  }
  80% {
    color: green;
  }
  100% {
    color: teal;
  }
}
@keyframes seizure-mode {
  0% {
    background-color: teal;
  }
  20% {
    background-color: gold;
  }
  40% {
    background-color: indianred;
  }
  60% {
    background-color: violet;
  }
  80% {
    background-color: green;
  }
  100% {
    background-color: teal;
  }
}
</style>
