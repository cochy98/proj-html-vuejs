<template>
  <div id="my-carousel">
    <div class="layover"></div>
    <div class="my-carousel-item">
      <img
        src="../../assets/images/home-parallax-144609983.jpg"
        alt="banner image"
        class="my-item-img"
      />
      <div class="my-item-description">
        <h3 class="text-white">Our Home Owners Say</h3>
        <div class="my-yellow-hr"></div>
        <img
          class="rounded-pill"
          src="../../assets/images/home-testimonial-113165296.jpg"
          alt="home-testimonial"
        />
        <p>
          “No man but feels more of a man in the world if he have but a bit of
          ground that he can call his own. However small it is on the surface,
          it is four thousand miles deep; and that is a very handsome property.”
        </p>
        <h6>Harry Smith new home owner</h6>
      </div>
    </div>
    <div class="points-item">
      <div class="current-item selected"></div>
      <div class="current-item"></div>
    </div>
    <div class="arch arch-top"></div>
    <div class="arch arch-bottom"></div>
  </div>
</template>

<script>
export default {
  name: "MainCarousel",
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "../../assets/scss/_variables.scss";

div#my-carousel {
  width: 100%;
  position: relative;

  div.arch {
    background-color: $light-gray-color;
  }

  div.points-item {
    position: absolute;
    bottom: 20%;
    left: 50%;
    transform: translate(-50%, 0);

    .current-item {
      width: 11px;
      height: 11px;
      margin: 0.2rem;
      border-radius: 50%;
      display: inline-block;
      border: 1px solid white;
    }

    .current-item.selected {
      background-color: white;
    }
  }

  div.my-carousel-item {
    img.my-item-img {
      width: 100%;
      height: 800px;
      object-fit: cover;
    }

    div.my-item-description {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      max-width: 650px;
      text-align: center;
      color: white;

      p {
        font-weight: 600;
        font-style: italic;
        margin: 1.2rem 0 1.8rem;
      }

      h6 {
        text-transform: uppercase;
        font-weight: 600;
      }
    }
  }
}
</style>
