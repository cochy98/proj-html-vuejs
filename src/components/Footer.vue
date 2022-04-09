<template>
  <footer>
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
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit error
          inventore esse eligendi earum sed minus quos nam nulla expedita et,
          deserunt eaque reiciendis a temporibus quia nobis explicabo! Eligendi.
        </p>
      </div>
    </section>
    <section id="footer-nav"></section>
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
    border: 2px solid rebeccapurple;
    color: white;
  }
}
</style>
