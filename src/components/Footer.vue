<template>
  <div class="container-fluid bg-light font-weight-bold text-secondary  ">
    <footer class="d-flex flex-column justify-content-center  mt-5">
      <div class="col-md grid-margin stretch-card">
        <div class="card borderopa">
          <div class="card-body">
            <h4 class="card-title "> 👌Tu peux nous joindre ici 😀</h4>

            <div class="template-demo">
              <button
                type="button"
                class="btn btn-social-icon btn-outline-facebook"
              >
                <i class="fa fa-facebook"></i>
              </button>
              <button
                type="button"
                class="btn btn-social-icon btn-outline-youtube"
              >
                <i class="fa fa-youtube"></i>
              </button>
              <button
                type="button"
                class="btn btn-social-icon btn-outline-twitter"
              >
                <i class="fa fa-twitter"></i>
              </button>
              <button
                type="button"
                class="btn btn-social-icon btn-outline-linkedin"
              >
                <i class="fa fa-linkedin"></i>
              </button>
              <button
                type="button"
                class="btn btn-social-icon btn-outline-instagram"
              >
                <i class="fa fa-instagram"></i>
              </button>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.borderopa{
box-shadow: 1px 5px 42px 2px rgba(23,162,184,0.64);
-webkit-box-shadow: 1px 5px 42px 2px rgba(23,162,184,0.64);
-moz-box-shadow: 1px 5px 42px 2px rgba(23,162,184,0.64);
border-radius:90px 20px 50px 20px;

}
</style>
