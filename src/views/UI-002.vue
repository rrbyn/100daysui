<template>
  <div class="test">
    <div class="errorMsgContainer">
      <form action="">
        <input type="submit" value="Go back" class="errorButton" />
      </form>
    </div>
    <div class="rightMessage">
      <div class="number">404</div>
      <div class="errorMsg">
        <span>Could not find the page you were looking for</span>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.test {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  color: #aba9a9;
  align-items: center;
  text-shadow: 1px black;
  height: 100vh;
}
.rightMessage {
  display: flex;
  flex-direction: column;
}
.number {
  font-size: 480px;
}

span {
  font-size: 32px;
}
.errorMsgContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.errorMsg {
  color: #a8a8a8;
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
  width: 16rem;
}
</style>
