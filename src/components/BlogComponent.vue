<template>
  <div class="creative_canvas_studio_tm_section" id="blog">
    <div class="creative_canvas_studio_tm_blog">
      <div class="container">
        <div class="creative_canvas_studio_tm_main_title" data-align="center">
          <span>From My Blog</span>
          <h3>Our Recent Updates, Blog, Tips, Tricks &amp; More</h3>
        </div>
        <div class="blog_list">
          <ul>
            <li class="wow fadeInUp" data-wow-duration="1s">
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/blog/responsive-design.jpg"></div>
                  <div class="date">
                    <h3>23</h3>
                    <span>Aug</span>
                  </div>
                  <a class="creative_canvas_studio_tm_full_link" href="#" @click.prevent="active = 1"></a>
                </div>
                <div class="details">
                  <span class="category">
                    <a href="#" @click.prevent="active = 1">The Art of Responsive Web Design</a>
                    </span>
                  <h3 class="title">
                    <a href="#" @click.prevent="active = 1">Explore the fundamentals of responsive web design, ensuring
                      seamless adaptability across diverse devices.</a>
                  </h3>
                </div>
              </div>
            </li>
            <li class="wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.2s">
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/blog/vue-js.jpg"></div>
                  <div class="date">
                    <h3>4</h3>
                    <span>Sep</span>
                  </div>
                  <a class="creative_canvas_studio_tm_full_link" href="#" @click.prevent="active = 2"></a>
                </div>
                <div class="details">
                  <span class="category">
                    <a href="#" @click.prevent="active = 2">The Power of JS Frameworks: Angular, React, and Vue</a>
                    </span>
                  <h3 class="title">
                    <a href="#" @click.prevent="active = 2">Discover the strengths of Angular, React, and Vue JavaScript frameworks, helping you choose the right one for your projects.</a>
                  </h3>
                </div>
              </div>
            </li>
            <li class="wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.4s">
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/blog/security.jpg"></div>
                  <div class="date">
                    <h3>12</h3>
                    <span>Sep</span>
                  </div>
                  <a class="creative_canvas_studio_tm_full_link" href="#" @click.prevent="active = 3"></a>
                </div>
                <div class="details">
                  <span class="category"><a href="#" @click.prevent="active = 3">Website Security Essentials: Protecting Your Digital Assets</a></span>
                  <h3 class="title">
                    <a href="#" @click.prevent="active = 3">Learn crucial website security aspects, from SSL certificates to coding best practices and defense against common web vulnerabilities.</a>
                  </h3>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/blog/1.png" alt="" />
      </div>
      <div class="brush_2 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/blog/2.png" alt="" />
      </div>
    </div>
  </div>
  <div :class="active == 1 ? '' : 'blog_hidden_details'">
    <ModalBox :close="close">
      <div class="blog_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div class="main" data-img-url="img/blog/responsive-design.jpg" style="background-image: url('img/blog/responsive-design.jpg')"></div>
        </div>
        <div class="details">
          <h3>The Art of Responsive Web Design</h3>
          <span><a href="#">Explore the fundamentals of responsive web design, ensuring seamless adaptability across diverse devices.</a></span>
          <div></div>
        </div>
        <div class="text">
          <p>
            In today's digital landscape, users access websites from a wide range of devices, from smartphones and tablets to desktop computers. To provide a consistent and user-friendly experience across these diverse platforms, responsive web design has become a crucial skill for web developers. 
          </p>
          <p>
            This article delves into the principles of responsive design, covering fluid grids, flexible images, and media queries. By mastering these techniques, you'll be equipped to create websites that look and function flawlessly on any screen, enhancing user satisfaction and boosting your web development prowess.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 2 ? '' : 'blog_hidden_details'">
    <ModalBox :close="close">
      <div class="blog_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div class="main" data-img-url="img/blog/vue-js.jpg" style="background-image: url('img/blog/vue-js.jpg')"></div>
        </div>
        <div class="details">
          <h3>HThe Power of JavaScript Frameworks: Angular, React, and Vue</h3>
          <span><a href="#">Discover the strengths of Angular, React, and Vue JavaScript frameworks, helping you choose the right one for your projects.</a></span>
          <div></div>
        </div>
        <div class="text">
          <p>
            JavaScript frameworks have redefined the landscape of web development, simplifying intricate tasks and accelerating the creation of dynamic web applications. In this article, we embark on an exploration of three prominent JavaScript frameworks: Angular, React, and Vue.
          </p>
          <p>
            We'll delve into the unique strengths and versatile use cases that make each of these frameworks stand out. Whether you are a seasoned developer or a newcomer to web development, this article will provide you with valuable insights into choosing the ideal framework for your specific project needs. Our goal is to empower you to make informed decisions, saving you time and ensuring the success of your web development endeavors.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 3 ? '' : 'blog_hidden_details'">
    <ModalBox :close="close">
      <div class="blog_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div class="main" data-img-url="img/blog/security.jpg" style="background-image: url('img/blog/security.jpg')"></div>
        </div>
        <div class="details">
          <h3>Website Security Essentials: Protecting Your Digital Assets</h3>
          <span><a href="#">Learn crucial website security aspects, from SSL certificates to coding best practices and defense against common web vulnerabilities.</a></span>
          <div></div>
        </div>
        <div class="text">
          <p>
            In today's digitally interconnected world, safeguarding your online assets is paramount. The increasing prevalence of cyber threats highlights the critical importance of website security. This article focuses on the essential aspects of website security, beginning with the significance of SSL certificates in encrypting data transmission, which is a fundamental step in protecting sensitive information. 
          </p>
          <p>
            We'll also explore best practices for writing secure code, equipping you with the knowledge to minimize vulnerabilities in your web applications. Furthermore, we'll delve into common web security threats, including SQL injection and cross-site scripting (XSS), and discuss strategies to fortify your web applications against these risks. By implementing robust security measures, you'll not only safeguard your users' data but also establish yourself as a responsible and trustworthy web developer in an era of increasing digital threats.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
</template>

<script>
import ModalBox from "./popup/ModalBox.vue";
export default {
  name: "BlogComponent",
  components: { ModalBox },
  data() {
    return {
      active: 0,
    };
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
};
</script>
