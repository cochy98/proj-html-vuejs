<template>
  <footer id="about">
    <section id="footer-partners" class="container">
      <div class="description-section">
        <h3>Trusted Partners</h3>
        <div class="my-yellow-hr"></div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi ad,
          hic, pariatur illum consectetur minima delectus laboriosam officia
          numquam
        </p>
      </div>
      <div class="row">
        <div class="col-12">
          <ul>
            <li>
              <img
                class="footer-partner-img"
                src="../assets/images/home-logo11-219096700-320x202.png"
                alt="Partner 1 Logo"
              />
            </li>
            <li>
              <img
                class="footer-partner-img"
                src="../assets/images/home-logo10-219096700-320x202.png"
                alt="Partner 2 Logo"
              />
            </li>
            <li>
              <img
                class="footer-partner-img"
                src="../assets/images/home-logo2-219096700-320x202.png"
                alt="Partner 3 Logo"
              />
            </li>
            <li>
              <img
                class="footer-partner-img"
                src="../assets/images/home-logo1-219096700-320x202.png"
                alt="Partner 4 Logo"
              />
            </li>
            <li>
              <img
                class="footer-partner-img"
                src="../assets/images/home-logo9-219096700-320x202.png"
                alt="Partner 5 Logo"
              />
            </li>
          </ul>
        </div>
      </div>
    </section>
    <section id="footer-banner">
      <div class="layover"></div>
      <img
        src="../assets/images/about-call-to-action-57862405.jpg"
        alt="Footer banner image"
        class="footer-banner-img"
      />
      <div class="footer-banner-desc container">
        <div class="my-col-left">
          <h3 class="text-white">Building Inspiring Spaces</h3>
          <div class="my-yellow-hr"></div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi
            ad, hic, pariatur illum consectetur minima delectus laboriosam
            officia numquam
          </p>
        </div>
        <div class="my-col-right">
          <button class="my-btn my-btn-yellow">Get a free quote</button>
          <p>Only takes a few seconds!</p>
        </div>
      </div>
    </section>
    <section id="footer-nav">
      <div class="max-hr"></div>
      <div class="container-fluid">
        <div class="row gx-5">
          <div class="col-info col-12 col-md-5 col-lg-3">
            <img
              src="../assets/images/footer-logo.png"
              alt="Avada Logo"
              class="footer-logo"
            />
            <p>
              We are specialists in the construction of unique and exclusive
              properties. Our work inspires. We pride ourselves on delivering
              outstanding quality and design for leading clients across the
              world.
            </p>
            <button class="my-btn my-btn-yellow">Learn more</button>
          </div>
          <div class="col-latest-tweets col-12 col-md-5 col-lg-3">
            <h6>Latest Tweets</h6>
            <div class="row">
              <div class="col-2">
                <img
                  src="../assets/images/3a74ce3d0532b7773b174c45ca3bd05a_bigger.png"
                  alt="fusion logo"
                  class="img-fluid rounded-pill"
                />
              </div>
              <div
                class="col-10 d-flex justify-content-between align-items-center"
              >
                <div>
                  <p class="fw-bold m-0">ThemeFusion</p>
                  <p class="m-0">@Theme_Fusion</p>
                </div>
                <img
                  src="../assets/images/image (1).svg"
                  alt="Twitter Icon"
                  class="social-icon"
                />
              </div>
              <div class="offset-2 col-10">
                <p>
                  Routine website maintenance is essential. Ensure that your
                  <span>#Avada</span> website & plugins are kept up to date.
                  Schedule regular backups, apply patches if required.
                  <span>How to Update https://bit.ly/2VLhHXo</span>
                </p>
                <img
                  src="../assets/images/En2TRxLW4AEiWUN.jpeg"
                  alt="Promo Image"
                  class="img-fluid"
                />
                <div class="row py-2">
                  <div
                    class="
                      col-12
                      d-flex
                      justify-content-between
                      align-items-center
                    "
                  >
                    <div>
                      <img
                        src="../assets/images/image (2).svg"
                        alt="Hearts Icon"
                        class="social-icon me-3"
                      />
                      <img
                        src="../assets/images/image (3).svg"
                        alt="Exit Icon"
                        class="social-icon"
                      />
                    </div>
                    <p class="m-0 promo-span">22h</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-contacts col-12 col-md-5 col-lg-3">
            <h6>Contact us today</h6>
            <ul>
              <li>
                <i class="fas fa-globe"></i>
                <div>
                  <p>Corporate Location</p>
                  <p>1600 Amphitheatre Parkway</p>
                  <p>London WC1 1BA</p>
                </div>
              </li>
              <li>
                <i class="fas fa-home"></i>
                <div>
                  <p>Residential Location</p>
                  <p>9521 Broadsberry Avenue</p>
                  <p>Paddington RC7 9ZA</p>
                </div>
              </li>
              <li>
                <i class="fas fa-phone"></i>
                <p>1.800.458.556 / 1.800.532.2112</p>
              </li>
              <li>
                <i class="far fa-envelope"></i>
                <p>info@your-domain.com</p>
              </li>
              <li>
                <i class="far fa-clock"></i>
                <p>Monday – Friday: 9:00 AM – 6:00 PM</p>
              </li>
              <li>
                <i class="far fa-clock"></i>
                <p>Saturday – Sunday: 9:00 AM – 12:00 PM</p>
              </li>
            </ul>
          </div>
          <div class="col-find-us col-12 col-md-5 col-lg-3">
            <h6>Find us</h6>
            <img src="../assets/images/map.png" alt="Map" class="img-fluid" />
          </div>
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
  name: "IndexFooter",
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "../assets/scss/_variables.scss";

section#footer-partners {
  padding-bottom: 5rem;

  ul {
    list-style-type: none;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;

    li {
      margin: 1rem;

      img.footer-partner-img {
        width: 210px;
      }
    }
  }
}

section#footer-banner {
  position: relative;
  width: 100%;

  img.footer-banner-img {
    width: 100%;
    height: 500px;
    object-fit: cover;
    object-position: bottom;
  }

  div.footer-banner-desc {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;

    div.my-col-left {
      flex-basis: 60%;

      div.my-yellow-hr {
        margin: 1rem 0 2rem;
      }
    }

    div.my-col-right {
      text-align: center;

      p {
        font-size: 0.8rem;
        margin: 0.45rem 0 0;
      }
    }
  }
}

section#footer-nav {
  background-color: #1e1e1e;
  color: $paragraph-color;
  font-size: 0.85rem;

  img.social-icon {
    width: 20px;
    filter: invert(41%) sepia(2%) saturate(7%) hue-rotate(189deg)
      brightness(101%) contrast(100%);
  }

  h6 {
    text-transform: uppercase;
    color: $secondary-color;
    margin-bottom: 2rem;
    font-weight: 600;
  }

  div.max-hr {
    height: 15px;
    background-color: #404040;
  }

  .container-fluid {
    padding: 5rem 4.5rem 0;

    div.col-info {
      img.footer-logo {
        height: 60px;
      }

      p {
        line-height: 1.8rem;
        margin: 1rem 0;
      }
    }

    div.col-latest-tweets {
      color: white;

      span {
        color: rgb(13, 100, 182);
      }

      p.promo-span {
        color: $paragraph-color;
      }
    }

    div.col-contacts {
      ul {
        padding: 0;
        margin: 0;

        li {
          display: flex;
          padding-bottom: 1rem;

          i {
            font-size: 1.1rem;
            padding-right: 0.6rem;
          }

          p {
            margin: 0;
          }
        }
      }
    }
  }

  .container-fluid > .row > div.col-12 {
    padding-bottom: 5rem;
  }
}
</style>
