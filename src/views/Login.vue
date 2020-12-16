<template>
  <div class="login">
    <div class="container">
      <div class="card login-card">
        <div class="row no-gutters">
          <div class="col-md-5">
            <img
              src="../assets/img/shutterstock_323883338 1.png"
              alt="login"
              class="login-card-img"
            />
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h2 class="card-title mt-5">Welcome Back</h2>
              <p class="card-subtitle mb-2">
                Please log in safely. Protect your log in information.
              </p>

              <form class="mt-5">
                 <div class="form-group col-9 mt-4 mx-3">
                    <label for="number" class="d-flex">Account Number</label>
                    <input type="number" name="number" id="number" class="form-control" >
                  </div>
                <div class="form-group col-9 mx-3">
                  <div class="d-flex justify-content-between">
                    <label>Password</label> <a href="#!" class="forgot-password-link text-orange">Forgot password?</a>
                  </div>
                  <input
                    type="password"
                    class="form-control"
                    placeholder="Password"
                  />
                </div>
                <div class="d-flex justify-content-around mt-5">
                   <button type="submit" class="btn btn-log">Login</button>
                <p class="mr-5">Don’t have an account? <router-link to="/register" class="text-orange">Sign up</router-link> </p>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.btn-log {
  background: #ff612d;
  color: #ffffff;
  padding: .4rem 1rem;
}
</style>
