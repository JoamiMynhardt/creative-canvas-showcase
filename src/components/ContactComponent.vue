<template>
  <div class="creative_canvas_studio_tm_section" id="contact">
    <div class="creative_canvas_studio_tm_contact">
      <div class="container">
        <div class="creative_canvas_studio_tm_main_title" data-align="center">
          <span>Get in Touch</span>
          <h3>I'm Here to Listen</h3>
          <p>
            Drop me a line, a joke, or a hello!
          </p>
        </div>
        <div class="contact_inner">
          <div class="left wow fadeInLeft" data-wow-duration="1s">
            <ul>
              <li>
                <div class="list_inner">
                  <div class="icon orangeBackground">
                    <i class="icon-location orangeText"></i>
                  </div>
                  <div class="short">
                    <h3>Address</h3>
                    <span>42 Innovation Avenue, Tech City, Digital District</span>
                  </div>
                </div>
              </li>
              <li>
                <div class="list_inner">
                  <div class="icon greenBackground">
                    <i class="icon-mail-1 greenText"></i>
                  </div>
                  <div class="short">
                    <h3>Email</h3>
                    <span><a href="#">hello@creative_canvas_studio.com</a></span>
                  </div>
                </div>
              </li>
              <li>
                <div class="list_inner">
                  <div class="icon purpleBackground">
                    <i class="icon-phone purpleText"></i>
                  </div>
                  <div class="short">
                    <h3>Phone</h3>
                    <span>+1 555 5555 5555</span>
                  </div>
                </div>
              </li>
            </ul>
          </div>
          <div class="right wow fadeInRight" data-wow-duration="1s">
            <div class="fields">
              <form
                action="/"
                method="post"
                class="contact_form"
                id="contact_form"
                autocomplete="off"
              >
                <div
                  class="returnmessage"
                  data-success="Your message has been received, We will contact you soon."
                ></div>
                <div class="empty_notice">
                  <span>Please Fill Required Fields</span>
                </div>
                <div class="input_list">
                  <ul>
                    <li>
                      <input id="name" type="text" placeholder="Your Name" />
                    </li>
                    <li>
                      <input id="email" type="text" placeholder="Your Email" />
                    </li>
                    <li>
                      <input
                        id="phone"
                        type="number"
                        placeholder="Your Phone"
                      />
                    </li>
                    <li>
                      <input id="subject" type="text" placeholder="Subject" />
                    </li>
                  </ul>
                </div>
                <div class="message_area">
                  <textarea
                    id="message"
                    placeholder="Write your message here"
                  ></textarea>
                </div>
                <div class="creative_canvas_studio_tm_button">
                  <a id="send_message" href="#"><span>Submit Now</span></a>
                </div>
              </form>
            </div>
          </div>
          <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
            <img src="img/brushes/contact/2.png" alt="" />
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="img/brushes/contact/1.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactComponent",
  components: {},
};
</script>
