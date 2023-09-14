<template>
  <div class="creative_canvas_studio_tm_section">
    <div class="creative_canvas_studio_tm_skills">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div
              class="creative_canvas_studio_tm_main_title wow fadeInUp"
              data-wow-duration="1s"
              data-align="left"
            >
              <span>Developing as a Way of Life</span>
              <h3>Continuous Skill Development for Staying Current</h3>
              <p>
                Utilizing Proven Techniques for Crafting Desktop-Optimized Websites
              </p>
            </div>
            <div class="dodo_progress wow fadeInUp" data-wow-duration="1s">
              <div
                class="progress_inner skillsInner___"
                data-value="85"
                data-color="#81c784"
              >
                <span
                  ><span class="label">Vue</span
                  ><span class="number">85%</span></span
                >
                <div class="background">
                  <div class="bar"><div class="bar_in"></div></div>
                </div>
              </div>
              <div
                class="progress_inner skillsInner___"
                data-value="95"
                data-color="#00acc1"
              >
                <span
                  ><span class="label">Tailwind CSS</span
                  ><span class="number">95%</span></span
                >
                <div class="background">
                  <div class="bar"><div class="bar_in"></div></div>
                </div>
              </div>
              <div
                class="progress_inner skillsInner___"
                data-value="75"
                data-color="#8067f0"
              >
                <span
                  ><span class="label">Figma</span
                  ><span class="number">75%</span></span
                >
                <div class="background">
                  <div class="bar"><div class="bar_in"></div></div>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <img :src="`/img/skills/skills.png`" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SkillComponent",
  components: {},
  props: {
    dark: { type: Boolean },
  },
};
</script>
