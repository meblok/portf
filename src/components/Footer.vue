<template>
  <div class="container-fluid justify-content-center px-0">
    <div class="card py-5 border-0 px-0 mx-0">
      <div class="card-body text-center">
        <div class="row justify-content-center">
          <!-- <div class="col-auto"><h6><b>Still have more questions ?</b></h6><small class="text-muted">Call/Text <span class="mx-2"><b>+91.1630.412.999</b></span>and with real person.</small>
                    <div class="row justify-content-center"><div class="col-10"><button type="button" class="btn btn-primary btn-lg btn-block my-5">Try it for free</button><h6> <b>100% Money Back Guarantee</b></h6> <small class="text-muted">If you'r not satsified for any reason, we'll refund your money</small></div></div>
                </div> -->
        </div>
      </div>
    </div>
    <footer>
      <div class="row justify-content-around mb-0 pt-5 mx-4">
        <!-- <div class="col-xl-2 col-md-4 order-xl-1 order-4 mr-xl-0 my-auto">
          <ul class="list-unstyled mt-md-3 mt-5">
            <li>Social Media</li>
            <li class="social">
              <span> <i class="fa fa-facebook" aria-hidden="true"></i></span>
              <span> <i class="fa fa-instagram" aria-hidden="true"></i> </span>
              <span> <i class="fa fa-twitter" aria-hidden="true"></i> </span>
            </li>
          </ul>
          <ul class="list-unstyled my-xl-4 my-md-3"></ul>
        </div> -->
        <div class="col-xl-2 col-md-3 pt-4 order-1">
          <ul class="list-unstyled">
            <li class="mt-md-0 mt-4">Su Solución</li>
            <li>Conocimientos</li>
            <li>Experiencia externa</li>
            <!-- <li>Product Features</li>
            <li>Pricing</li> -->
          </ul>
        </div>
        <div class="col-xl-2 col-md-3 pt-4 order-2">
          <ul class="list-unstyled">
            <li class="mt-md-0 mt-4">Su Necesidad</li>
            <li>Disciplina</li>
            <li>Puntualidad</li>
            <!-- <li>Product Features</li>
            <li>Pricing</li> -->
          </ul>
        </div>
        <div class="col-xl-auto col-md-3 pt-4 my-sm-0 order-md-3 order-sm-1">
          <ul class="list-unstyled">
            <li class="mt-md-0 mt-4">Ofresco</li>
            <li>Estabilidad</li>
            <li>Ganas</li>
           <!--  <li>Product Features</li>
            <li>Pricing</li> -->
          </ul>
        </div>
        <!-- <div class="col-xl-auto col-md-6 col-12 pt-4 my-sm-0 order-6">
          <div class="form-group">
            <label for="email" class="mb-3"
              ><b>Subscribe to our newsletter and Get 10% off</b></label
            ><input
              type="email"
              class="form-control form-control-lg"
              placeholder="Enter email"
              id="email"
            />
          </div>
          <button
            type="button"
            class="btn btn-primary btn-lg btn-block my-2 Subscribe mt-4 mb-3"
          >
            Subscribe
          </button>
        </div> -->
      </div>
      <br /><br />
      <section class="mb-4 text-center">
        <!-- Facebook -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-facebook-f"></i
        ></a>

        <!-- Twitter -->
        <!--     <a
           class="btn btn-outline-light btn-floating m-1"
           href="#!"
           role="button"
           ><i class="fab fa-twitter"></i
          ></a> -->

        <!-- Google -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-google"></i
        ></a>

        <!-- Instagram -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-instagram"></i
        ></a>

        <!-- Linkedin -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="https://www.linkedin.com/in/alfonso1/" 
          target="_blank"
          role="button"
          ><i class="fab fa-linkedin-in"></i
        ></a>

        <!-- Github -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="https://github.com/meblok"
          role="button"
          ><i class="fab fa-github"></i
        ></a>
      </section>
      <div class="row justify-content-center px-3 py-3 pt-5">
        <div class="col text-center"><p class="mb-0"></p></div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Muli&display=swap");
body {
  font-family: "Muli", sans-serif;
  height: 100% !important;
  background-color: #fff !important;
  padding-bottom: 0 !important;
  margin-bottom: 0 !important;
  overflow-x: hidden;
}
.card {
  color: #383431 !important;
  background-color: #ffffff !important;
}

h5 {
  font-size: calc(
    20px + (28 - 20) * ((100vw - 360px) / (1600 - 360))
  ) !important;
}
.fa {
  cursor: pointer;
  font-size: 21px;
  margin: 5px 10px 5px 10px !important;
}

button {
  font-size: calc(
    13px + (16 - 13) * ((100vw - 360px) / (1600 - 320))
  ) !important;
  border-radius: 0 !important;
  padding-left: calc(
    20px + (28 - 20) * ((100vw - 360px) / (1600 - 360))
  ) !important;
  padding-right: calc(
    20px + (28 - 20) * ((100vw - 360px) / (1600 - 360))
  ) !important;
  padding-top: calc(
    10px + (12 - 10) * ((100vw - 360px) / (1600 - 360))
  ) !important;
  padding-bottom: calc(
    10px + (12 - 10) * ((100vw - 360px) / (1600 - 360))
  ) !important;
  background-color: #383431 !important;
  border: none !important;
}

button:focus {
  -moz-box-shadow: none !important;
  -webkit-box-shadow: none !important;
  box-shadow: none !important;
  outline-width: 0;
}

li {
  margin-top: 8px;
  margin-bottom: 8px;
}

input::-webkit-input-placeholder {
  padding-left: 5px !important;
  transform: translate3d(0, -2px, 0);
}

input::placeholder {
  vertical-align: middle !important;
  color: rgb(196, 193, 193) !important;
  font-size: calc(
    12px + (14 - 12) * ((100vw - 360px) / (1600 - 360))
  ) !important;
}

input {
  border-radius: 2px !important;
  background: transparent !important;
  color: #ffffff !important;
}

input:focus {
  -moz-box-shadow: none !important;
  -webkit-box-shadow: none !important;
  box-shadow: none !important;
  outline-width: 0;
  border-color: #ffffff !important;
}

img {
  vertical-align: middle !important;
  width: 100%;
  width: calc(30px + 6 * ((100vw - 320px) / 680)) !important;
}

li:first-child {
  font-size: 18px !important;
  font-weight: bold;
}

footer {
  background-color: #383431 !important;
  color: #ffffff !important;
}

small {
  font-size: calc(
    12px + (14 - 12) * ((100vw - 360px) / (1600 - 360))
  ) !important;
}

p {
  font-size: calc(
    12px + (14 - 12) * ((100vw - 360px) / (1600 - 360))
  ) !important;
  color: rgb(196, 193, 193) !important;
}

.social {
  position: relative;
  left: -10px;
}

.Subscribe {
  background-color: #ffffff !important;
  color: #383431 !important;
  font-weight: bold;
}

li:not(:first-child) {
  color: rgb(196, 193, 193) !important;
}
</style>