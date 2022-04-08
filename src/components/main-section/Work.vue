<template>
  <section id="work">
    <div class="description-section">
      <h3>Explore Recent Work</h3>
      <div class="my-yellow-hr"></div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
        hic, pariatur illum consectetur minima delectus laboriosam officia
        numquam
      </p>
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
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/project1-featured-294276386-400x400.jpg"
              alt="Cart image 2"
              class="cart-image"
            />
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/project3-featured-189023420-400x400.jpg"
              alt="Cart image 3"
              class="cart-image"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="end-section container pt-3 pb-5">
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
div#carts-work {
  div.cart {
    margin: 1rem 0;

    img.cart-image {
      width: 100%;
      height: 100%;
    }
  }
}
</style>
