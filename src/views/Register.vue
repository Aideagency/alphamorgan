<template>
  <div class="register">
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
              <h2 class="card-title mt-5">Create Account</h2>
              <p class="card-subtitle mb-2">
                Already have an account?
                <router-link to="/login" class="text-orange">Login</router-link>
              </p>

              <form class="row g-3 mt-5 mx-5">
                <div class="col-12 mt-3">
                  <label for="lastName" class="form-label d-flex"
                    >Last Name <span class="text-orange">*</span></label
                  >
                  <input type="text" class="form-control" id="lastName" />
                </div>
                <div class="col-md-6 mt-3">
                  <label for="firstName" class="form-label d-flex"
                    >First Name <span class="text-orange">*</span></label
                  >
                  <input type="text" class="form-control" id="firstName" />
                </div>
                <div class="col-md-6 mt-3">
                  <label for="otherNames" class="form-label d-flex"
                    >Other Names</label
                  >
                  <input type="text" class="form-control" id="otherNames" />
                </div>

                <div class="col-12 mt-3">
                  <label for="email" class="form-label d-flex"
                    >Email <span class="text-orange">*</span></label
                  >
                  <input type="email" class="form-control" id="email" />
                </div>
                <div class="col-md-6 mt-3">
                  <label for="inputCity" class="form-label d-flex"
                    >Phone Number <span class="text-orange">*</span></label
                  >
                  <input type="number" class="form-control" id="number" />
                </div>
                <div class="col-md-6 mt-3">
                  <label for="bvn" class="form-label d-flex"
                    >BVN <span class="text-orange">*</span></label
                  >
                  <input type="number" class="form-control" id="bvn" />
                </div>

                <div class="col-12 d-flex mt-5">
                  <button type="submit" class="btn btn-log">Next</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>

      <!-- account security setup -->
      <div class="card login-card mt-5">
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
              <h2 class="card-title mt-5">YOMI,</h2>
              <p class="mb-2">
                You’re doing great already, Let’s set your login details
              </p>

              <form class="row g-3 mt-5 mx-5">
                <div class="col-12 mt-3">
                  <label for="userName" class="form-label d-flex"
                    >User Name <span class="text-orange">*</span></label
                  >
                  <input type="text" class="form-control" id="userName" />
                </div>

                <div class="col-12 mt-3">
                  <label for="passName" class="form-label d-flex"
                    >Enter Password <span class="text-orange">*</span></label
                  >
                  <input type="text" class="form-control" id="passName" />
                </div>

                <div class="col-12 mt-3">
                  <label for="conPass" class="form-label d-flex"
                    >Confirm Password <span class="text-orange">*</span></label
                  >
                  <input type="text" class="form-control" id="ConPass" />
                </div>

                <span class="mx-3 my-3"
                  >To continue account setup tick the box to continue</span
                >

                <div class="form-check mx-3 my-2">
                  <input
                    class="form-check-input"
                    type="checkbox"
                    id="gridCheck1"
                  />
                  <label class="form-check-label" for="gridCheck1">
                    Accept our
                    <span class="text-orange">“Terms and Conditions”</span>
                  </label>
                </div>

                <div class="col-12 d-flex justify-content-between mt-5">
                  <button type="submit" class="btn btn-prev">Previous</button>
                  <button type="submit" class="btn btn-log">Next</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>

      <!-- product page stock  -->
      <div class="card login-card mt-5">
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
              <h2 class="card-title mt-5">YOMI,</h2>
              <p class="card-subtitle mb-2">
                Select a product to complete account creation
              </p>
              <h3 class="mt-5">
                Avaible products
              </h3>
              <form class="row g-3 mt-5 mx-5">
                <div class="col-12 mt-3">
                  <label for="amount" class="form-label d-flex">Amount</label>
                  <input type="text" class="form-control" id="amount" />
                </div>

                <div class="col-12 mt-3">
                  <label for="mandate" class="form-label d-flex">Mandate</label>
                  <textarea
                    class="form-control"
                    id="mandate"
                    rows="3"
                  ></textarea>
                </div>

                <div class="col-12 d-flex justify-content-between mt-5">
                  <button type="submit" class="btn btn-prev">Previous</button>
                  <button type="submit" class="btn btn-log">Submit</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>

      <!-- submit response -->
      <div class="card login-card mt-5">
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
              <h2 class="card-title mt-5">YOMI,</h2>
              <p class="card-subtitle mb-2 text-center m-5">
                Thank you for submitting your mandate we will review it within
                48 working hours and get back to you. If approved, it will be
                indicated in your dashboard
              </p>

              <div class="col-12 d-flex justify-content-center mt-3">
                <button type="submit" class="btn btn-log text-center mt-5">
                  View Dashboard
                </button>
              </div>
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
  padding: 0.4rem 2rem;
}

.btn-prev {
  background: #d0d0d0;
  color: #ffffff;
  padding: 0.4rem 2rem;
}
</style>
