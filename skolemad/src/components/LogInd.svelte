<head
  ><link
    href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css"
    rel="stylesheet"
    id="bootstrap-css"
  />
  <script
    src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
  <script
    src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script></head
>
<body>
  <div id="login">
    <h3 class="text-center text-white pt-5">Login form</h3>
    <div class="container">
      <div id="login-row" class="row justify-content-center align-items-center">
        <div id="login-column" class="col-md-6">
          <div id="login-box" class="col-md-12">
            <form id="login-form" class="form" action="" method="post">
              <h4>Log ind på SkoleMad</h4>
              <div class="form-group">
                <label for="username">Brugernavn/id:</label><br />
                <input
                  type="text"
                  name="username"
                  id="username"
                  class="form-control"
                />
              </div>
              <div class="form-group">
                <label for="password">Kodeord:</label><br />
                <input
                  type="text"
                  name="password"
                  id="password"
                  class="form-control"
                />
              </div>
              <div class="form-group">
                <label for="remember-me"
                  ><span>Husk mig</span>
                  <span
                    ><input
                      id="remember-me"
                      name="remember-me"
                      type="checkbox"
                    /></span
                  ></label
                ><br />
                <div>
                  <input
                    type="submit"
                    name="submit"
                    class="submit_knap btn btn-info btn-md"
                    value="Log ind"
                  />
                  <input
                    type="submit"
                    name="submit"
                    class="anuller_knap btn btn-info btn-md"
                    value="Anunller"
                  />
                </div>
              </div>
              <div>
                <p>Glemt kodeord???????</p>
                <p>Har du ikke en konto</p>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>

<style>
  body {
    margin: 0;
    padding: 0;
    color: var(--font);
    height: 100vh;
  }
  h4 {
    font-size: var(--heading-five-m);
  }
  #login .container #login-row #login-column #login-box {
    margin-top: 120px;
    max-width: 600px;
    height: 320px;
    border: 1px solid #9c9c9c;
    background-color: var(--box-color);
    border-radius: var(--border-rounded);
    border-color: #55c000;
  }
  #login .container #login-row #login-column #login-box #login-form {
    padding: 20px;
  }

  #login
    .container
    #login-row
    #login-column
    #login-box
    #login-form
    #register-link {
    margin-top: -85px;
  }
  #username {
    border-color: #55c000;
  }
  #password {
    border-color: #55c000;
  }
  .submit_knap {
    color: var(--white);
    background-color: #55c000;
    transition: 0.2s ease;
    padding: var(--spacing-1) var(--spacing-1);
    max-width: 15rem;
    border-radius: var(--border-rounded);
    border: none;
    cursor: pointer;
    display: inline-block;
  }
  .anuller_knap {
    color: var(--btn-danger-font);
    background-color: var(--btn-danger);
    transition: 0.2s ease;
    padding: var(--spacing-1) var(--spacing-1);
    max-width: 15rem;
    border-radius: var(--border-rounded);
    border-color: var(--bth-danger);
    cursor: pointer;
    display: inline-block;
  }
</style>
