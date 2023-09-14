<template>
  <div class="creative_canvas_studio_tm_section" id="about">
    <div class="creative_canvas_studio_tm_about">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div class="image">
              <img :src="`/img/about/about.png`" alt="" />
              <div class="numbers year">
                <div class="wrapper">
                  <h3>
                    <VueJsCounter end="10"></VueJsCounter>
                  </h3>
                  <span class="name">Years of<br />Success</span>
                </div>
              </div>
              <div class="numbers project">
                <div class="wrapper">
                  <h3 style="display: flex">
                    <VueJsCounter as="span" end="50"></VueJsCounter>
                  </h3>
                  <span class="name">Total<br />Projects</span>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <div class="title wow fadeInUp" data-wow-duration="1s">
              <span>I'm a Frontend Developer</span>
              <h3>Crafting Engaging User Experiences</h3>
            </div>
            <div class="text wow fadeInUp" data-wow-duration="1s">
              <p>
                Passionate and versatile professional with 7+ years of experience in video editing, animation, and front-end development. Specializing in creating captivating animations and seamlessly edited videos, I continuously refine my skills in Vue.js, Tailwind CSS, and Blender. Proficient in tools like After Effects, Adobe Illustrator, and Photoshop, I bring ideas to life with precision and creativity.
              </p>
            </div>
            <div class="creative_canvas_studio_tm_button wow fadeInUp" data-wow-duration="1s">
              <a class="anchor" href="#contact"><span>Hire Me</span></a>
            </div>
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/img/brushes/about/1.png" alt="" />
      </div>
      <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/about/2.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
import VueJsCounter from "vue-js-counter";
export default {
  name: "AboutComponent",
  components: { VueJsCounter },
  props: {
    dark: { type: Boolean },
  },
};
</script>
