<template>
  <div class="creative_canvas_studio_tm_section" id="portfolio">
    <div class="creative_canvas_studio_tm_portfolio">
      <div class="container">
        <div class="creative_canvas_studio_tm_main_title" data-align="center">
          <span>Portfolio</span>
          <h3>Showcasing My Development Journey</h3>
          <p>
            Credit for designs belong to Envato
          </p>
        </div>
        <div class="portfolio_filter">
          <ul>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '1' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '1')"
                data-filter="*"
                >All</a
              >
            </li>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '2' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '2')"
                data-filter=".mobile-sign-up"
                >Mobile Design</a
              >
            </li>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '3' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '3')"
                data-filter=".landing-page"
                >Landing Page</a
              >
            </li>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '4' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '4')"
                data-filter=".sign-up-form"
                >Sign Up Forms</a
              >
            </li>
          </ul>
        </div>
        <div class="creative_canvas_studio_tm_portfolio_titles"></div>
        <div class="portfolio_list wow fadeInUp" data-wow-duration="1s">
          <ul class="gallery_zoom grid">
            <li class="mobile-sign-up grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Mobile Sign Up 1"
                  data-category="Mobile Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', '/img/portfolio/mobile-sign-up-1.jpg')"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/mobile-sign-up-1.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Mobile Sign Up 1</h3>
                  <span>Mobile Design</span>
                </div>
              </div>
            </li>
            <li class="landing-page grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Landing Page 1"
                  data-category="Website Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', '/img/portfolio/landing-page-1.jpg')"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/landing-page-1.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Landing Page 1</h3>
                  <span>Website Design</span>
                </div>
              </div>
            </li>
            <li class="sign-up-form grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Sign Up Form"
                  data-category="Website Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', '/img/portfolio/sign-up-form.jpg')"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/sign-up-form.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Sign Up Form</h3>
                  <span>Website Design</span>
                </div>
              </div>
            </li>
            <li class="mobile-sign-up grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Mobile Sign Up 2"
                  data-category="Mobile Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', 'img/portfolio/mobile-sign-up-2.jpg')"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/mobile-sign-up-2.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Mobile Sign Up 2</h3>
                  <span>Mobile Design</span>
                </div>
              </div>
            </li>
            <li class="landing-page grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Landing Page 3"
                  data-category="Website Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', 'img/portfolio/landing-page-3.jpg')"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/landing-page-3.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Landing Page 3</h3>
                  <span>Website Design</span>
                </div>
              </div>
            </li>
            <li class="landing-page grid-item">
              <div class="inner">
                <div
                  class="entry creative_canvas_studio_tm_portfolio_animation_wrap"
                  data-title="Landing Page 2"
                  data-category="Website Design"
                >
                  <a
                    class="zoom"
                    href="#"
                    @click.prevent="() => onClick('img', 'img/portfolio/landing-page-2.jpg')"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/landing-page-2.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Landing Page 2</h3>
                  <span>Website Design</span>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/portfolio/1.png" alt="" />
      </div>
      <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/portfolio/2.png" alt="" />
      </div>
    </div>
  </div>
  <MagnificPopUpVue
    :modal="modal"
    :close="closeModal"
    :name="name"
    :src="src"
  />
</template>

<script>
import MagnificPopUpVue from "./popup/MagnificPopUp.vue";
export default {
  name: "PortfolioComponent",
  data() {
    return {
      activeNav: "1", // props
      name: "",
      src: "",
      modal: false,
      // Content
      active: 0,
    };
  },
  mounted() {
    let Isotope = require("isotope-layout");
    setTimeout(() => {
      let iso = new Isotope(".gallery_zoom", {
        itemSelector: ".grid-item",
        //    layoutMode: "fitRows",
        percentPosition: true,
        masonry: {
          columnWidth: ".grid-item",
        },
        animationOptions: {
          duration: 750,
          easing: "linear",
          queue: false,
        },
      });
      let filterFns = {
        // show if number is greater than 50
        numberGreaterThan50: function (itemElem) {
          let number = itemElem.querySelector(".number").textContent;
          return parseInt(number, 10) > 50;
        },
        // show if name ends with -ium
        ium: function (itemElem) {
          let name = itemElem.querySelector(".name").textContent;
          return name.match(/ium$/);
        },
      };
      // bind filter button click filter main funtion
      let filtersElem = document.querySelector(".portfolio_filter ul");
      filtersElem.addEventListener("click", function (event) {
        if (event.target.getAttribute("data-filter")) {
          let filterValue = event.target.getAttribute("data-filter");
          filterValue = filterFns[filterValue] || filterValue;
          iso.arrange({ filter: filterValue });
        }
      });
    }, 1000);
  },
  methods: {
    onClick(name, src) {
      this.name = name;
      this.src = src;
      this.modal = true;
    },
    closeModal() {
      this.modal = false;
      this.name = "";
      this.src = "";
    },
    close() {
      this.active = 0;
    },
  },
  components: { MagnificPopUpVue },
};
</script>
