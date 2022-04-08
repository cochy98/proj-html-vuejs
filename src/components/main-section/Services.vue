<template>
  <section id="service">
    <div class="description-section">
      <h3>Specialists In Modern Construction</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
        hic, pariatur illum consectetur minima delectus laboriosam officia
        numquam
      </p>
    </div>
    <div id="cart-service" class="container-fluid p-5">
      <div class="row p-5">
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <div class="cart my-flex-column-center">
            <span class="my-flex-center">
              <i class="far fa-building"></i>
            </span>
            <h3 class="my-3">Buidings</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Id dolor
              nesciunt suscipit officiis assumenda quod cumque
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <div class="cart my-flex-column-center">
            <span class="my-flex-center">
              <i class="fas fa-sync"></i>
            </span>
            <h3 class="my-3">Renovate</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Id dolor
              nesciunt suscipit officiis assumenda quod cumque
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <div class="cart my-flex-column-center">
            <span class="my-flex-center">
              <i class="fas fa-home"></i>
            </span>
            <h3 class="my-3">Construct</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Id dolor
              nesciunt suscipit officiis assumenda quod cumque
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <div class="cart my-flex-column-center">
            <span class="my-flex-center">
              <i class="fas fa-truck"></i>
            </span>
            <h3 class="my-3">Exclusive</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Id dolor
              nesciunt suscipit officiis assumenda quod cumque
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MainServices",
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "@/assets/scss/_variables.scss";

div#cart-service {
  div.cart {
    width: 100%;
    background-color: $light-gray-color;
    text-align: center;
    padding: 2rem;
    border-radius: 0.8rem;
    color: $paragraph-color;

    span {
      width: 75px;
      height: 75px;
      border: 1px solid $paragraph-color;
      border-radius: 50%;

      i {
        font-size: 1.6rem;
      }
    }

    h3 {
      color: $primary-color;
    }

    p {
      margin-bottom: 0;
      line-height: 1.8rem;
    }
  }
}
</style>
