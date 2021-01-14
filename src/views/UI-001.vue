<template>
  <div class="flex-center">
    <div class="login-card">
      <form class="login-form">
        <h1>Create a new account</h1>
        <div class="form-group">
          <label for="email">Your E-mail</label>
          <input type="email" id="email" />
        </div>
        <div class="form-group">
          <label for="password">Password</label>
          <input type="password" id="password" />
        </div>
        <div class="terms">
          <a href="#terms">
            <small>Terms and conditions</small>
          </a>
        </div>
        <button type="submit">Sign up</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.login {
  &-card {
    width: 300px;
    background: #171a21;
    box-shadow: 0 18px 30px rgba(0, 0, 0, 0.06);
    padding: 3rem;
    border-radius: 8px;
    text-align: left;
    h1 {
      margin-top: 0;
      margin-bottom: 1em;
      font-size: 3em;
      letter-spacing: -2px;
      color: white;
    }
    button {
      padding: 20px;
      background: linear-gradient(to right, #47bfff 5%, #1a44c2 60%);
      border: none;
      border-radius: 4px;
      display: block;
      width: 100%;
      color: white;
      font-weight: 600;
      cursor: pointer;
      &:hover {
        background: linear-gradient(to right, #47bfff 5%, #1a44c2 60%);
        opacity: 0.8;
      }
    }
  }
}
.form-group {
  display: flex;
  flex-direction: column;
  margin-bottom: 2rem;
  input {
    border: none;

    padding: 10px 5px;
    background: #696f7d;
  }
  label {
    margin-bottom: 5px;
    color: #afafaf;
    font-size: 0.7rem;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  &:hover {
    input {
      border-color: #47bfff;
    }
    label {
      color: #8d8d8d;
    }
  }
}
.form-group input:focus {
  outline-style: solid;
  outline-color: #1a44c2;
  border-color: #47bfff;
}
.terms {
  a {
    color: darkgray;
    text-decoration: none;
    &:hover {
      color: gray;
    }
  }
  text-align: center;
  margin-bottom: 1rem;
}
</style>
