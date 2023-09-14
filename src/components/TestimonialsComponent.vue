<template>
  <div class="creative_canvas_studio_tm_section" id="testimonials">
    <div class="creative_canvas_studio_tm_testimonials">
      <div class="creative_canvas_studio_tm_main_title" data-align="center">
        <span>Testimonials</span>
        <h3>Client Success Stories</h3>
        <p>
          What My Clients Are Saying About My Expertise in Responsive and Adaptive Web Design
        </p>
      </div>
      <div class="list_wrapper">
        <div class="total">
          <div class="in">
            <swiper
              :pagination="{ clickable: true, el: '.owl-dots' }"
              :modules="modules"
              class="owl-carousel owl-theme"
            >
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    Working with Joami Mynhardt was a game-changer for our web development needs. Joami's expertise and attention to detail resulted in a website that exceeded our expectations. Joami truly understands the balance between aesthetics and functionality.
                  </p>
                </div>
                <div class="short">
                  <div class="detail">
                    <h3>Sarah Mitchell</h3>
                    <span>Director of Marketing, Acme Solutions Inc.</span>
                  </div>
                </div>
              </swiper-slide>
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    I cannot recommend Joami Mynhardt enough for their outstanding web development work. Joami's dedication to our project, along with their technical prowess, resulted in a website that not only looks amazing but also performs exceptionally well. We're extremely satisfied with the results.
                  </p>
                </div>
                <div class="short">
                  <div class="detail">
                    <h3>Michael Rodriguez</h3>
                    <span>Founder & CEO, Horizon Tech Labs</span>
                  </div>
                </div>
              </swiper-slide>
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    Joami Mynhardt took our web presence to the next level. Their strategic approach to web development, paired with a keen eye for design, transformed our online platform. The increased user engagement and positive feedback we've received are a testament to Joami's expertise.
                  </p>
                </div>
                <div class="short">
                  <div class="detail">
                    <h3>Emily Chang</h3>
                    <span>VP of Operations, Stellar Innovations</span>
                  </div>
                </div>
              </swiper-slide>
            </swiper>
            <div class="owl-dots"></div>
          </div>
          <div class="left_details">
            <span class="circle green animPulse"></span>
            <span class="circle yellow animPulse"></span>
            <span class="circle border animPulse"></span>
          </div>
          <div class="right_details">
            <span class="circle yellow animPulse"></span>
            <span class="circle purple animPulse"></span>
            <span class="circle border animPulse"></span>
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/testimonials/1.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
import { testimonialIcon } from "@/svg";
import { Pagination } from "swiper";
import { Swiper, SwiperSlide } from "vue-awesome-swiper";
export default {
  name: "TestimonialsComponent",
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return {
      testimonialIcon,
    };
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
};
</script>
