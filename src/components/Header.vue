<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><img
            class="nav-logo"
            src="../assets/images/construction_logo_retina.png"
            alt="Construction Logo"
        /></a>
        <!-- Button hamburger visualizzato da medium in giu -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#linkCollapsed"
          aria-controls="linkCollapsed"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="linkCollapsed"
        >
          <ul class="navbar-nav">
            <li class="nav-item" v-for="(link, index) in navLinks" :key="index">
              <a
                class="nav-link"
                :class="link.active ? 'active' : ''"
                :href="link.href"
                >{{ link.name }}</a
              >
            </li>
            <button class="my-btn my-btn-yellow" type="submit">
              Get Quote
            </button>
          </ul>
        </div>
      </div>
    </nav>
    <div id="header-jumbotron">
      <img
        class="img-jumbo"
        src="../assets/images/home-slider-62528242.jpg"
        alt="Header Jumbo image"
      />
    </div>
  </header>
</template>

<script>
export default {
  name: "IndexHeader",
  data() {
    return {
      navLinks: [
        {
          active: true,
          name: "Home",
          href: "#",
        },
        {
          active: false,
          name: "About",
          href: "#",
        },
        {
          active: false,
          name: "Services",
          href: "#",
        },
        {
          active: false,
          name: "Work",
          href: "#",
        },
        {
          active: false,
          name: "Articles",
          href: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
/* Importo le variabili scss */
@import "../assets/scss/_variables.scss";

header {
  nav {
    font-size: 0.95rem;
    padding: 0.9rem 3.5rem;

    img.nav-logo {
      height: 60px;
    }

    ul .nav-item {
      padding-right: 1.4rem;
    }

    ul.navbar-nav a.nav-link {
      text-transform: uppercase;
      color: $paragraph-color;
    }
    ul.navbar-nav a.nav-link.active {
      color: $secondary-color;
    }
  }

  div#header-jumbotron {
    width: 100%;
    height: 600px;
    position: relative;

    img.img-jumbo {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
  }
}
</style>
