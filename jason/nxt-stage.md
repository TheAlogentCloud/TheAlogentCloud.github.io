## NXT Tether Login Test - nxt-stage

Current site target - [https://nxt-stage.alogent.com/app](https://nxt-stage.alogent.com/app)

### Login Form

<form action="https://nxt-stage.alogent.com/app/api/Authentication/TetheredLogin" method="POST">
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
