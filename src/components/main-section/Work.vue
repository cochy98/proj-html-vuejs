<template>
  <section id="work">
    <div class="container">
      <div class="description-section">
        <h3>Explore Recent Work</h3>
        <div class="my-yellow-hr"></div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
          hic, pariatur illum consectetur minima delectus laboriosam officia
          numquam
        </p>
      </div>
    </div>
    <div id="carts-work" class="container py-4">
      <div class="row">
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/project2-featured-15013609.jpg"
              alt="Cart image 1"
              class="cart-image"
            />
            <div class="cart-hover">
              <div class="cart-description text-center text-white">
                <div class="icon"><i class="fas fa-link"></i></div>
                <div class="icon"><i class="fas fa-search"></i></div>
                <h5>Florida Heath Facility</h5>
                <p>Commercial</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/project1-featured-294276386-400x400.jpg"
              alt="Cart image 2"
              class="cart-image"
            />
            <div class="cart-hover">
              <div class="cart-description text-center text-white">
                <div class="icon"><i class="fas fa-link"></i></div>
                <div class="icon"><i class="fas fa-search"></i></div>
                <h5>Florida Heath Facility</h5>
                <p>Commercial</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/project3-featured-189023420-400x400.jpg"
              alt="Cart image 3"
              class="cart-image"
            />
            <div class="cart-hover">
              <div class="cart-description text-center text-white">
                <div class="icon"><i class="fas fa-link"></i></div>
                <div class="icon"><i class="fas fa-search"></i></div>
                <h5>Florida Heath Facility</h5>
                <p>Commercial</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="end-section container pt-2 pb-4">
      <div class="row">
        <div class="col-12">
          <h6>View all projects</h6>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MainWork",
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "../../assets/scss/_variables.scss";

div#carts-work {
  div.cart {
    margin: 1rem 0;
    position: relative;

    img.cart-image {
      width: 100%;
      height: 100%;
    }

    div.cart-hover {
      display: none;
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0;
      background-color: $secondary-color;

      div.icon {
        display: inline-block;
        width: 60px;
        height: 60px;
        line-height: 60px;
        margin: 0.5rem;
        background-color: white;
        color: $secondary-color;
        font-size: 1.6rem;
        border-radius: 50%;
      }
    }
  }

  div.cart:hover div.cart-hover {
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>
