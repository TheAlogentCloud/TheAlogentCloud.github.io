## NXT Tether Login Test - test-digital

Current site target - [https://test-digital.alogent.com/app](https://test-digital.alogent.com/app)

### Login Form

<form action="https://test-digital.alogent.com/app/api/Authentication/TetheredLogin" method="POST">
  <label for="username">Username</label>
  <input type="text" name="username" />
  <br/>
  <label for="password">Password</label>
  <input type="password" name="password" />
  <br/>
  <label for="password">Redirect</label>
  <input type="text" name="redirectParam" placeholder="ex: /user/sso-select/open-account" />
  <br/>
  <input type="submit" name="Submit" />
</form>
