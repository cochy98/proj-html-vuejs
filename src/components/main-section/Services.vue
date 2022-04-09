<template>
  <section id="service">
    <div class="description-section container">
      <h3>Specialists In Modern Construction</h3>
      <div class="my-yellow-hr"></div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
        hic, pariatur illum consectetur minima delectus laboriosam officia
        numquam
      </p>
    </div>
    <div id="cart-service" class="container-fluid pt-5 px-5">
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
    <div id="banner">
      <div class="layover"></div>
      <img
        src="../../assets/images/home-244125289.jpg"
        alt="banner image"
        class="banner-img"
      />
      <div class="banner-description container">
        <div class="row">
          <div class="col-6 col-lg-3">
            <i class="fas fa-suitcase"></i>
            <h1>3534</h1>
            <p>Planning applications</p>
          </div>
          <div class="col-6 col-lg-3">
            <i class="far fa-building"></i>
            <h1>896</h1>
            <p>Completed projects</p>
          </div>
          <div class="col-6 col-lg-3">
            <i class="fas fa-users"></i>
            <h1>172</h1>
            <p>Trained professionals</p>
          </div>
          <div class="col-6 col-lg-3">
            <i class="fas fa-globe"></i>
            <h1>19</h1>
            <p>International offices</p>
          </div>
        </div>
      </div>
      <div class="arch arch-top"></div>
      <div class="arch arch-bottom"></div>
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
@import "../../assets/scss/_variables.scss";

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

    p {
      margin-bottom: 0;
      line-height: 1.8rem;
    }
  }
}

div#banner {
  width: 100%;
  position: relative;

  img.banner-img {
    width: 100%;
    height: 660px;
    object-fit: cover;
  }

  div.banner-description {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: $secondary-color;
    text-align: center;

    i {
      font-size: 3.2rem;
    }

    h1 {
      font-weight: 500;
    }

    p {
      color: white;
      text-transform: uppercase;
    }
  }
}
</style>
