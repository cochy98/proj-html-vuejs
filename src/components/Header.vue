<template>
  <header>
    <nav id="header-nav" class="navbar navbar-expand-lg navbar-light bg-light">
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
      <div class="layover"></div>
      <img
        class="img-jumbo"
        src="../assets/images/home-slider-62528242.jpg"
        alt="Header Jumbo image"
      />
      <div class="jumbo-description">
        <h1 class="text-uppercase text-white mb-4">
          Building inspiring spaces
        </h1>
        <p class="my-text-yellow fs-5 mb-4">
          We build Inspiring Residential & Commercial Spaces
        </p>
        <button class="my-btn me-2">Explore recent work</button>
        <button class="my-btn my-btn-yellow ms-2">Get a quote today</button>
      </div>
      <div class="jumbotron-span">
        <span>
          <i class="fas fa-folder"></i>
          <p class="mb-0">Demos</p>
        </span>
        <span>
          <i class="fas fa-dollar-sign text-success"></i>
          <p class="mb-0">On Sale</p>
        </span>
      </div>
    </div>
    <div
      id="header-bottom"
      class="d-flex justify-content-center align-items-center"
    >
      <h3 class="text-center my-color-title my-fw-400 m-0">
        Do You Have A Construction Project We Can Help With?
      </h3>
      <button class="my-btn">Get a free quote</button>
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
    height: 700px;
    position: relative;

    div.layover {
      position: absolute;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.3);
    }

    div.jumbo-description {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }

    img.img-jumbo {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    div.jumbotron-span {
      position: absolute;
      top: 0;
      right: 0;
      padding: 2rem 1rem;

      span {
        display: block;
        width: 85px;
        height: 85px;
        border-radius: 0.6rem;
        margin-bottom: 0.6rem;
        background-color: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;

        i {
          font-size: 2rem;
        }
      }
    }
  }

  div#header-bottom {
    height: 120px;
    background-color: $secondary-color;
    position: relative;

    button {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translate(-50%, 1.5rem);
      border: 2px solid white;
    }
  }
}
</style>
