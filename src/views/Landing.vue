<template>
  <div class="landing">
    <Navbar />
    <div class="card bg-dark text-white">
      <img src="../assets/img/HOME BANNER.png" class="card-img" alt="..." />
      <div class="card-img-overlay">
        <div class="row">
          <div class="col-3">
            <div class="card">
              <div class="card-header">
                <h6 class="text-dark">Access Portal</h6>
              </div>
              <b-tabs content-class="mt-3" justified>
                <b-tab title="Sign in" active>
                  <router-link to="/login" class="btn btn-log"
                    >Login</router-link
                  >
                  <p class="text-muted mt-3">Retrive Login Details</p>
                </b-tab>
                <b-tab title="Register">
                  <router-link to="/register" class="btn btn-log"
                    >Register</router-link
                  >
                  <p class="text-muted mt-3">Retrive Register Details</p>
                </b-tab>
              </b-tabs>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row my-5">
        <div class="col-md-12">
          <h3 class="text-center">Our product</h3>
          <p class="text-center">
            We think life should be sweet, so we’ve built world class <br />
            products and services to make life easier
          </p>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-6">
          <div class="card mb-4">
            <img
              src="../assets/img/landinimg.png"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body px-3 py-4">
              <h5 class="card-title d-flex">FIXED RATE INCOME (FRI)</h5>
              <p class="card-text">
                Providing expert advice and a wide range of financial products
                and services to grow wealth Providing expert advice and a wide
                range of financial products and services to grow wealth
              </p>
              <a href="#" class="card-link text-orange d-flex">Subscribe</a>
            </div>
          </div>
        </div>

        <div class="col-sm-6">
          <div class="card mb-4">
            <img
              src="../assets/img/landinimg.png"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body px-3 py-4">
              <h5 class="card-title d-flex">MUTUAL FUND</h5>
              <p class="card-text">
                Providing expert advice and a wide range of financial products
                and services to grow wealth Providing expert advice and a wide
                range of financial products and services to grow wealth
              </p>
              <a href="#" class="card-link text-orange d-flex">Subscribe</a>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-6">
          <div class="card mb-4">
            <img
              src="../assets/img/landinimg.png"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body px-3 py-4">
              <h5 class="card-title d-flex">STOCK</h5>
              <p class="card-text">
                Providing expert advice and a wide range of financial products
                and services to grow wealth Providing expert advice and a wide
                range of financial products and services to grow wealth
              </p>
              <a href="#" class="card-link text-orange d-flex">Subscribe</a>
            </div>
          </div>
        </div>

        <div class="col-sm-6">
          <div class="card mb-4">
            <img
              src="../assets/img/landinimg.png"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body px-3 py-4">
              <h5 class="card-title d-flex">BONDS</h5>
              <p class="card-text">
                Providing expert advice and a wide range of financial products
                and services to grow wealth Providing expert advice and a wide
                range of financial products and services to grow wealth
              </p>
              <a href="#" class="card-link text-orange d-flex">Subscribe</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container my-5">
      <div class="d-flex justify-content-between">
        <h5>ALPHA MORGAN FIXED RATE INCOME</h5>
        <div class="d-flex">
          <p class="mr-3">NGN (N)</p>
          <p>USD ($)</p>
        </div>
      </div>
      <table class="table table-bordered border-dark table-sm">
        <thead>
          <tr>
            <th scope="col">Amount (Naira)</th>
            <th scope="col" colspan="5">% per annum, per duration</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td></td>
            <td>30days</td>
            <td>60days</td>
            <td>90days</td>
            <td>180days</td>
            <td>365days</td>
          </tr>
          <tr>
            <td>1,000,000 - 5,999,999</td>
            <td>2</td>
            <td>2.5</td>
            <td>3</td>
            <td>3.5</td>
            <td>4</td>
          </tr>
          <tr>
            <td>6,000,000 - 10,999,999</td>
            <td>3</td>
            <td>3.5</td>
            <td>4</td>
            <td>4.5</td>
            <td>5</td>
          </tr>
          <tr>
            <td>11,000,000 - 30,999,999</td>
            <td>4</td>
            <td>4.5</td>
            <td>5</td>
            <td>5.5</td>
            <td>6</td>
          </tr>
          <tr>
            <td>31,000,000 - 50,999,999</td>
            <td>5</td>
            <td>5.5</td>
            <td>6</td>
            <td>6.5</td>
            <td>7</td>
          </tr>
          <tr>
            <td>51,000,000 - 100,999,999</td>
            <td>6</td>
            <td>6.5</td>
            <td>7</td>
            <td>7.5</td>
            <td>8</td>
          </tr>
          <tr>
            <td>101,000,000 and Above</td>
            <td>7</td>
            <td>7.5</td>
            <td>8</td>
            <td>8.5</td>
            <td>9</td>
          </tr>
        </tbody>
      </table>

      <table class="table table-bordered border-dark table-sm" style="display: none;">
        <thead>
          <tr>
            <th scope="col">Amount (US Dollars)</th>
            <th scope="col" colspan="5">% per annum, per duration</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td></td>
            <td>90days</td>
            <td>180days</td>
            <td>365days</td>
          </tr>
          <tr>
            <td>10,000 - 49,999</td>
            <td>2.00%</td>
            <td>2.25%</td>
            <td>2.50%</td>
          </tr>
          <tr>
            <td>50,000 - 99,999</td>
            <td>2.50%</td>
            <td>3.00%</td>
            <td>3.25%</td>
          </tr>
          <tr>
            <td>100,000 - 499,999</td>
            <td>3.25%</td>
            <td>3.50%</td>
            <td>3.75%</td>
          </tr>
          <tr>
            <td>500,000 - 999,999</td>
            <td>3.75%</td>
            <td>4.00%</td>
            <td>4.25%</td>
          </tr>
          <tr>
            <td>1,000,000 and Above</td>
            <td>4.25%</td>
            <td>4.50%</td>
            <td>5.00%</td>
          </tr>
        </tbody>
      </table>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
export default {
  name: 'Landing',
  components: {
    Navbar,
    Footer
  },
  data () {
    return {
      fields: ['Amount (Naira)', 'last_name', 'age'],
      items: [
        { age: 40, first_name: 'Dickerson', last_name: 'Macdonald' },
        { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
        { age: 89, first_name: 'Geneva', last_name: 'Wilson' }
      ]
    }
  }
}
</script>

<style>
.btn-log {
  background: #ff612d;
  color: #ffffff;
  padding: 0.4rem 2rem;
}

.card-img-overlay {
  position: absolute !important;
  bottom: 0 !important;
  right: 0 !important;
}
</style>
