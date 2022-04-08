<template>
  <section id="articles" class="my-5">
    <div class="container pt-5">
      <div class="description-section">
        <h3>Our Core Values</h3>
        <div class="my-yellow-hr"></div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
          hic, pariatur illum consectetur minima delectus laboriosam officia
          numquam
        </p>
      </div>
      <div id="carts-property">
        <div class="row">
          <div class="col-6 col-lg-3">
            <div class="cart my-flex-column-center">
              <span class="my-flex-center bg-cyan">
                <i class="fas fa-home"></i>
              </span>
              <h6>Great Services</h6>
              <div class="my-light-hr"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                dolor, beatae repudiandae
              </p>
            </div>
          </div>
          <div class="col-6 col-lg-3">
            <div class="cart my-flex-column-center">
              <span class="my-flex-center bg-lg-blue">
                <i class="fas fa-cog"></i>
              </span>
              <h6>Highrest Standards</h6>
              <div class="my-light-hr"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                dolor, beatae repudiandae
              </p>
            </div>
          </div>
          <div class="col-6 col-lg-3">
            <div class="cart my-flex-column-center">
              <span class="my-flex-center bg-orange">
                <i class="fas fa-users"></i>
              </span>
              <h6>Professional Team</h6>
              <div class="my-light-hr"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                dolor, beatae repudiandae
              </p>
            </div>
          </div>
          <div class="col-6 col-lg-3">
            <div class="cart my-flex-column-center">
              <span class="my-flex-center bg-lg-green">
                <i class="far fa-lightbulb"></i>
              </span>
              <h6>Creative Solutions</h6>
              <div class="my-light-hr"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                dolor, beatae repudiandae
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MainArticles",
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "../../assets/scss/_variables.scss";

section#articles {
  background-color: $light-gray-color;

  div#carts-property {
    div.cart {
      width: 100%;
      height: 280px;
      text-align: center;
      padding: 0 0.7rem;
      color: $paragraph-color;

      span {
        width: 95px;
        height: 95px;
        font-size: 3rem;
        border-radius: 50%;
        color: white;
      }

      h6 {
        font-weight: 400;
        padding: 0.6rem 0 0.2rem;
      }

      div.my-light-hr {
        width: 20px;
        height: 2px;
        border-bottom: 2px solid $paragraph-color;
      }

      p {
        font-size: 0.85rem;
        line-height: 1.6rem;
        margin-top: 0.7rem;
      }
    }
  }
}
</style>
