<template>
  <section
    :style="{ backgroundImage: `url(${bgImage})` }"
    class="section-hero section-shaped my-0"
  >
    <div class="shape shape-style-1 shape-primary"></div>
    <div class="container shape-container d-flex align-items-center">
      <div class="col px-0">
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-7 text-center pt-lg">
            <!-- <img
              src="img/brand/main-logo-alt.png"
              style="width: 200px;box-shadow: 10px 10px 12px rgba(255,255,255,.6);"
              class="img-fluid"
            />-->
            <h1 class="display-1 text-white mt-4 mb-5">
              Blue Key Property
              <br />Management
            </h1>
            <a
              class="loginButton"
              href="https://jessicawatts.managebuilding.com/Resident/PublicPages/login.aspx"
              target="_blank"
              >SIGN IN</a
            >
            <!-- <div class="btn-wrapper">
              <base-button
                tag="a"
                href="https://demos.creative-tim.com/vue-argon-design-system/documentation"
                class="mb-3 mb-sm-0"
                type="info"
                icon="fa fa-code"
              >Components</base-button>
              <base-button
                tag="a"
                href="https://www.creative-tim.com/product/vue-argon-design-system"
                class="mb-3 mb-sm-0"
                type="white"
                icon="ni ni-cloud-download-95"
              >Download Vue</base-button>
            </div>-->
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import bgImage from "../../../public/img/brand/banner-cottage.jpg";

export default {
  data() {
    return {
      bgImage: bgImage,
    };
  },
};
</script>
<style>
.loginButton {
  background-color: #b3cc6f;
  padding: 12px;
  border-radius: 5px;
}
</style>
