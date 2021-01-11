<template>
  <div class="test">
    <div class="errorMsgContainer">
      <div class="errorMsg">Could not find the page you were looking for</div>
      <button type="submit" class="errorButton">Go back</button>
    </div>
    <div class="numbers">404</div>
  </div>
</template>
<style lang="scss" scoped>
* {
  background-color: #696f7d;
}

.test {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  color: white;
  align-items: center;
  text-shadow: 1px 1px black;
}
.numbers {
  font-size: 384px;
}
.errorMsgContainer {
  display: flex;
  flex-direction: column;
}
.errorButton {
  background-color: white;
  border: none;
  color: lightgrey;
  padding: 5px;
  text-align: center;
  text-decoration: none;
  font-size: 32px;
}
</style>
