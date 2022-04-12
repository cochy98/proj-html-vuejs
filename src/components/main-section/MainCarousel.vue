<template>
  <div id="my-carousel" @mouseleave="autoPlay" @mouseover="stopAutoPlay">
    <div class="layover"></div>
    <div
      class="my-carousel-items"
      v-for="(element, index) in carouselImages"
      :key="index"
    >
      <div
        class="my-carousel-item"
        :class="activeElement === index ? 'd-block' : 'd-none'"
      >
        <img :src="element.source" :alt="element.title" class="my-item-img" />
        <div class="my-item-description">
          <h3 class="text-white">{{ element.title }}</h3>
          <div class="my-yellow-hr"></div>
          <img
            class="rounded-pill"
            :src="element.author.image"
            :alt="element.author.name"
          />
          <p>
            {{ element.description }}
          </p>
          <h6>{{ element.author.name }}</h6>
        </div>
      </div>
    </div>
    <div class="points-item">
      <div
        class="current-item"
        :class="activeElement === index ? 'selected' : ''"
        v-for="(element, index) in carouselImages"
        :key="index"
        @click="changeActive(index)"
      ></div>
    </div>
    <div class="arch arch-top"></div>
    <div class="arch arch-bottom"></div>
  </div>
</template>

<script>
export default {
  name: "MainCarousel",
  data() {
    return {
      activeElement: 0,
      hasAutoPlay: null,
      carouselImages: [
        {
          title: "Our Home Owners Say",
          description:
            "“No man but feels more of a man in the world if he have but a bit of\
          ground that he can call his own. However small it is on the surface,\
          it is four thousand miles deep; and that is a very handsome property.”",
          source: require("../../assets/images/home-parallax-144609983.jpg"),
          author: {
            image: require("../../assets/images/home-testimonial-113165296.jpg"),
            name: "Harry Smith new home owner",
          },
        },
        {
          title: "Titolo 2",
          description: "“La mia biografiaaaaa”",
          source: require("../../assets/images/blog-post-92486644-400x241.jpg"),
          author: {
            image: require("../../assets/images/home-testimonial-84268399.jpg"),
            name: "Io sono l'autore",
          },
        },
        {
          title: "Titolo 3",
          description:
            "“No man but feels more of a man in the world if he have but a bit of\
          ground that he can call his own. However small it is on the surface,\
          it is four thousand miles deep; and that is a very handsome property.”",
          source: require("../../assets/images/home-parallax-144609983.jpg"),
          author: {
            image: require("../../assets/images/home-testimonial-113165296.jpg"),
            name: "Harry Smith new home owner",
          },
        },
      ],
    };
  },
  methods: {
    nextImage: function () {
      if (this.activeElement === this.carouselImages.length - 1) {
        this.activeElement = 0;
      } else {
        this.activeElement++;
      }
    },
    autoPlay: function () {
      console.warn("parto con l'autoPlay");
      this.hasAutoPlay = setInterval(() => {
        this.nextImage();
      }, 3000);
    },
    stopAutoPlay: function () {
      clearInterval(this.hasAutoPlay);
      console.warn("ok, mi fermo!");
    },
    changeActive: function (newIndex) {
      this.activeElement = newIndex;
    },
  },
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
