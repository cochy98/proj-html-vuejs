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
            it is four thousand miles deep; and that is a very handsome
            property.”
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
    <div class="container">
      <div class="description-section">
        <h3>Latest News</h3>
        <div class="my-yellow-hr"></div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
          hic, pariatur illum consectetur minima delectus laboriosam officia
          numquam
        </p>
      </div>
    </div>
    <div id="latest-news" class="container py-4">
      <div class="row gy-4">
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/blog-post-134132600.jpg"
              alt="Cart image 1"
              class="cart-image"
            />
            <div class="cart-body">
              <h4 class="cart-title">
                Redeveloping Florida's Remote Southern Coast
              </h4>
              <p class="cart-date">December 7th, 2015</p>
              <hr />
              <p class="cart-content">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Aspernatur, dolores inventore provident rem sint quaerat laborum
                quos architecto in debitis perferendis dolore accusantium
                nostrum delectus adipisci reiciendis voluptas vitae quia.
              </p>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/blog-post-92486644.jpg"
              alt="Cart image 1"
              class="cart-image"
            />
            <div class="cart-body">
              <h4 class="cart-title">
                How We Manage Large Construction Projects
              </h4>
              <p class="cart-date">December 7th, 2015</p>
              <hr />
              <p class="cart-content">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Aspernatur, dolores inventore provident rem sint quaerat laborum
                quos architecto in debitis perferendis dolore accusantium
                nostrum delectus adipisci reiciendis voluptas vitae quia.
              </p>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="cart">
            <img
              src="../../assets/images/blog-post-332773904.jpg"
              alt="Cart image 1"
              class="cart-image"
            />
            <div class="cart-body">
              <h4 class="cart-title">Future proofing a modern home</h4>
              <p class="cart-date">December 6th, 2015</p>
              <hr />
              <p class="cart-content">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Aspernatur, dolores inventore provident rem sint quaerat laborum
                quos architecto in debitis perferendis dolore accusantium
                nostrum delectus adipisci reiciendis voluptas vitae quia.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="end-section row py-5">
        <div class="col-12">
          <h6>View all articles</h6>
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

  div#latest-news {
    div.cart {
      height: 100%;
      background-color: white;

      img.cart-image {
        width: 100%;
        max-height: 250px;
        object-fit: cover;
      }

      div.cart-body {
        padding: 2rem;
        color: $paragraph-color;

        h4.cart-title {
          font-weight: 400;
        }

        p.cart-date {
          font-size: 0.8rem;
          margin-bottom: 1.4rem;
        }
      }
    }
  }
}
</style>
