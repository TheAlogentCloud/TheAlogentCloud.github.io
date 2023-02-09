## NXT Tether Login Test - SkyOne Test

Current site target - [https://nxt-skyone-test.alogentcloud.com/app](https://nxt-skyone-test.alogentcloud.com/app)

### Login Form

<form action="https://nxt-skyone-test.alogentcloud.com/app/api/Authentication/TetheredLogin" method="POST">
  <label for="username">Username</label>
  <input type="text" name="username" id="userName" />
  <br/>
  <label for="password">Password</label>
  <input type="password" name="password" id="password" />
  <br/>
  <label for="redirectParam">Redirect</label>
  <input type="text" name="redirectParam" id="redirectParam" placeholder="ex: /user/sso-select/open-account" />
  <br/>
  <input type="submit" name="Submit" />
</form>
