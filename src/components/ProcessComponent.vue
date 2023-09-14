<template>
  <div class="creative_canvas_studio_tm_section" id="process">
    <div class="creative_canvas_studio_tm_process">
      <div class="container">
        <div class="list">
          <ul>
            <li class="wow fadeInUp" data-wow-duration="1s">
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? pixelPerfectDark : pixelPerfectLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Targeted Solutions</h3>
                </div>
                <div class="text">
                  <p>
                    I craft precise and custom solutions, hitting the bullseye of your project's needs. I aim for excellence in every line of code.
                  </p>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? highQualityDark : highQualityLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Creative Development</h3>
                </div>
                <div class="text">
                  <p>
                    Like a skilled artist with a brush, I paint your ideas into reality. My development process combines creativity and technical expertise to deliver outstanding results.
                  </p>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.4s"
            >
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? awesomeIdeaDark : awesomeIdeaLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Bright Ideas, Brighter Solutions</h3>
                </div>
                <div class="text">
                  <p>
                    Innovation is my guiding light. I illuminate your path with cutting-edge development strategies, transforming your ideas into impactful solutions.
                  </p>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  awesomeIdeaDark,
  awesomeIdeaLight,
  highQualityDark,
  highQualityLight,
  pixelPerfectDark,
  pixelPerfectLight,
} from "@/svg";
export default {
  name: "ProcessComponent",
  data() {
    return {
      pixelPerfectLight,
      highQualityDark,
      awesomeIdeaDark,
      pixelPerfectDark,
      awesomeIdeaLight,
      highQualityLight,
    };
  },
  components: {},
  props: {
    dark: { type: Boolean },
  },
};
</script>
