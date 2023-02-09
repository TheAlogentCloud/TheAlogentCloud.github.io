## NXT Tether Login Test - localhost

Current site target - [https://localhost:5001](https://localhost:5001)

### Login Form

<form action="https://localhost:5001/api/Authentication/TetheredLogin" method="POST">
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
