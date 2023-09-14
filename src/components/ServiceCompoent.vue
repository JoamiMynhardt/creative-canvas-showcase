<template>
  <div class="creative_canvas_studio_tm_section" id="service">
    <div class="creative_canvas_studio_tm_services">
      <div class="container">
        <div class="creative_canvas_studio_tm_main_title" data-align="center">
          <span>Services</span>
          <h3>My Client-Centric Approach</h3>
          <p>
            Utilizing Proven Techniques for Desktop Website Design: Responsive and Adaptive Design
          </p>
        </div>
        <div class="service_list">
          <ul>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
              @click.prevent="active = 1"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/anchor.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/1.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Creative development</h3>
                </div>
                <div class="text">
                  <p>
                    Unleashing Digital Potential - Transforming ideas into robust digital solutions.
                  </p>
                </div>
                <a class="creative_canvas_studio_tm_full_link" href="#"></a>
                <img
                  class="popup_service_image"
                  src="/img/service/1.jpg"
                  alt=""
                />
              </div>
            </li>
            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
              @click.prevent="active = 2"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/physics.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/2.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Building Digital Bridges</h3>
                </div>
                <div class="text">
                  <p>
                    Building Digital Bridges - Creating seamless online experiences.
                  </p>
                </div>
                <a class="creative_canvas_studio_tm_full_link" href="#"></a>
                <img
                  class="popup_service_image"
                  src="/img/service/2.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        In today's interconnected world, building meaningful connections is essential. I specialize in crafting digital experiences that bridge the gap between your brand and its audience. My expertise lies in designing and developing platforms that foster engagement, communicate your message effectively, and enhance the overall user journey.
                      </p>
                      <p>
                        Through a user-centric approach, I ensure that your digital presence connects with users on a deep level. I collaborate closely with you to understand your unique objectives and your target audience's needs. Together, we'll build digital bridges that not only meet but exceed your goals, leaving a lasting impact in the digital landscape.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
              @click.prevent="active = 3"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/contact.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/3.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>UI/UX Design</h3>
                </div>
                <div class="text">
                  <p>
                    Crafting User-Centric Experiences - Elevating digital interactions.
                  </p>
                </div>
                <a class="creative_canvas_studio_tm_full_link" href="#"></a>
                <img
                  class="popup_service_image"
                  src="/img/service/3.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        UI/UX design is about more than just aesthetics; it's about creating memorable and intuitive user experiences. I specialize in developing interfaces that are not only visually striking but also highly functional. From initial wireframes to pixel-perfect designs, I ensure that every interaction is thoughtfully crafted to resonate with your audience.
                      </p>
                      <p>
                        By placing users at the center of the design process, I help you establish a connection with your users that goes beyond the surface. Through extensive research, prototyping, and iterative testing, I'll collaborate closely with you to ensure that your digital product meets the unique needs and expectations of your target audience. Let's work together to elevate your digital interactions and make a lasting impression.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
              @click.prevent="active = 4"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/web.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/4.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Web Design</h3>
                </div>
                <div class="text">
                  <p>
                    Shaping Digital Identities - Powering your online presence.
                  </p>
                </div>
                <a class="creative_canvas_studio_tm_full_link" href="#"></a>
                <img
                  class="popup_service_image"
                  src="/img/service/4.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        Your website is your digital identity, and it should make a strong statement. I specialize in crafting web designs that not only captivate but also resonate with your brand's essence. With a focus on responsive design and captivating visuals, I'll ensure that your website not only looks impressive but also functions seamlessly across devices.
                      </p>
                      <p>
                        Through a deep understanding of your brand identity and target audience, I'll work closely with you to create a website that aligns perfectly with your goals. From user-friendly navigation to engaging content presentation, I'll shape your digital identity to leave a lasting impact on visitors and reinforce your online presence. Let's collaborate to make your digital presence a powerful tool for success.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/img/brushes/service/5.png" alt="" />
      </div>
      <div class="brush_2 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/service/6.png" alt="" />
      </div>
    </div>
  </div>
  <div :class="active == 1 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/1.jpg"
            style="background-image: url('img/service/1.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Creative Design</h3>
        </div>
        <div class="descriptions">
          <p>
            Creative development is at the heart of what I do. I specialize in turning concepts into reality by crafting web applications, interactive experiences, and innovative software solutions. My expertise lies in leveraging technology to bring your vision to life. Whether it's enhancing user experiences, solving complex problems, or making meaningful connections with your audience, I'm here to help you succeed.
          </p>
          <p>
            With a focus on creative problem-solving and meticulous attention to detail, I'll work closely with you to ensure that your digital projects align with your goals and exceed your expectations. Let's embark on a journey to unlock your digital potential, one project at a time.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 2 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/2.jpg"
            style="background-image: url('img/service/2.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Building Digital Bridges</h3>
        </div>
        <div class="descriptions">
          <p>
            In today's interconnected world, building meaningful connections is essential. I specialize in crafting digital experiences that bridge the gap between your brand and its audience. My expertise lies in designing and developing platforms that foster engagement, communicate your message effectively, and enhance the overall user journey.
          </p>
          <p>
            Through a user-centric approach, I ensure that your digital presence connects with users on a deep level. I collaborate closely with you to understand your unique objectives and your target audience's needs. Together, we'll build digital bridges that not only meet but exceed your goals, leaving a lasting impact in the digital landscape.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 3 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/3.jpg"
            style="background-image: url('img/service/3.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>UI/UX Design</h3>
        </div>
        <div class="descriptions">
          <p>
            UI/UX design is about more than just aesthetics; it's about creating memorable and intuitive user experiences. I specialize in developing interfaces that are not only visually striking but also highly functional. From initial wireframes to pixel-perfect designs, I ensure that every interaction is thoughtfully crafted to resonate with your audience.
          </p>
          <p>
            By placing users at the center of the design process, I help you establish a connection with your users that goes beyond the surface. Through extensive research, prototyping, and iterative testing, I'll collaborate closely with you to ensure that your digital product meets the unique needs and expectations of your target audience. Let's work together to elevate your digital interactions and make a lasting impression.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 4 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/4.jpg"
            style="background-image: url('img/service/4.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Web Design</h3>
        </div>
        <div class="descriptions">
          <p>
            Your website is your digital identity, and it should make a strong statement. I specialize in crafting web designs that not only captivate but also resonate with your brand's essence. With a focus on responsive design and captivating visuals, I'll ensure that your website not only looks impressive but also functions seamlessly across devices.
          </p>
          <p>
            Through a deep understanding of your brand identity and target audience, I'll work closely with you to create a website that aligns perfectly with your goals. From user-friendly navigation to engaging content presentation, I'll shape your digital identity to leave a lasting impact on visitors and reinforce your online presence. Let's collaborate to make your digital presence a powerful tool for success.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
</template>

<script>
import ModalBox from "./popup/ModalBox.vue";
export default {
  name: "ServiceCompoent",
  data() {
    return {
      active: 0,
    };
  },
  mounted() {
    let VanillaTilt = require("vanilla-tilt");
    VanillaTilt.init(document.querySelectorAll(".tilt-effect"), {
      maxTilt: 6,
      easing: "cubic-bezier(.03,.98,.52,.99)",
      speed: 500,
      transition: true,
    });
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
  components: { ModalBox },
  props: {
    dark: { type: Boolean },
  },
};
</script>
