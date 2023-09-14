<template>
  <div class="creative_canvas_studio_tm_section" id="home">
    <div class="creative_canvas_studio_tm_hero">
      <div
        class="background"
        :data-img-url="`/img/slider/bg.jpg`"
      ></div>
      <div class="container">
        <div class="content">
          <div class="details">
            <div class="hello">
              <h3 class="orangeText">Hello, I'm</h3>
            </div>
            <div class="name">
              <h3>Joami Mynhardt</h3>
            </div>
            <div class="job">
              <p>
                A <span class="greenText">frontend developer</span> from
                <span class="purpleText">Tech City</span>
              </p>
            </div>
            <div class="text">
              <p>
                I'm frontend developer based in Tech City, and I'm very passionate and dedicated to my work.
              </p>
            </div>
            <div class="button">
              <div class="creative_canvas_studio_tm_button">
                <a class="anchor" href="#about"><span>About Me</span></a>
              </div>
              <div class="social">
                <ul>
                  <li>
                    <a href="https://www.youtube.com/@codemotionlabs/videos" target="_blank"><i class="icon-youtube-1"></i></a>
                  </li>
                  <li>
                    <a href="https://www.linkedin.com/in/joami-mynhardt/" target="_blank"><i class="icon-linkedin-1"></i></a>
                  </li>
                  <li>
                    <a href="https://github.com/JoamiMynhardt" target="_blank"><i class="icon-git"></i></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="avatar">
            <div class="image">
              <img src="/img/slider/avatar.png" alt="" />
              <span class="skills vue anim_moveBottom" v-html="vue"></span>
              <span class="skills tailwindcss anim_moveBottom" v-html="tailwindcss"></span>
              <span class="skills figma anim_moveBottom" v-html="figma"></span>
            </div>
          </div>
        </div>
      </div>
      <div class="creative_canvas_studio_tm_down">
        <a class="anchor" href="#process" v-html="dark ? mouseDark : mouse">
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { vue, figma, mouse, mouseDark, tailwindcss } from "../svg";
export default {
  name: "HomeComponent",
  data() {
    return { vue, tailwindcss, figma, mouse, mouseDark };
  },
  props: {
    dark: { type: Boolean },
  },
};
</script>
