<template>
  <div class="home-container">
    <app-navbar></app-navbar>
    <main class="home-main">
      <div class="section-container">
        <div class="home-max-width max-content-container">
          <div class="home-content-container">
            <h1 class="home-text heading1">
              <span>
                Feed all your news sources and mailboxes right into
                <span v-html="rawx54s"></span>
              </span>
              <span class="home-text02">
                Feedbox
                <span v-html="rawno0p"></span>
              </span>
            </h1>
            <div class="home-input-container">
              <div class="home-container1 input">
                <svg viewBox="0 0 804.5714285714286 1024" class="home-icon">
                  <path
                    d="M804.571 708.571c0 20.571-9.143 60.571-17.714 79.429-12 28-44 46.286-69.714 60.571-33.714 18.286-68 29.143-106.286 29.143-53.143 0-101.143-21.714-149.714-39.429-34.857-12.571-68.571-28-100-47.429-97.143-60-214.286-177.143-274.286-274.286-19.429-31.429-34.857-65.143-47.429-100-17.714-48.571-39.429-96.571-39.429-149.714 0-38.286 10.857-72.571 29.143-106.286 14.286-25.714 32.571-57.714 60.571-69.714 18.857-8.571 58.857-17.714 79.429-17.714 4 0 8 0 12 1.714 12 4 24.571 32 30.286 43.429 18.286 32.571 36 65.714 54.857 97.714 9.143 14.857 26.286 33.143 26.286 50.857 0 34.857-103.429 85.714-103.429 116.571 0 15.429 14.286 35.429 22.286 49.143 57.714 104 129.714 176 233.714 233.714 13.714 8 33.714 22.286 49.143 22.286 30.857 0 81.714-103.429 116.571-103.429 17.714 0 36 17.143 50.857 26.286 32 18.857 65.143 36.571 97.714 54.857 11.429 5.714 39.429 18.286 43.429 30.286 1.714 4 1.714 8 1.714 12z"
                  ></path>
                </svg>
                <input
                  type="text"
                  placeholder="Your phone number..."
                  class="home-textinput input"
                />
              </div>
              <button class="home-button button-primary button">
                Get started
              </button>
            </div>
            <div class="home-features-container">
              <div class="home-feature">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon02">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text03">
                  Easiest way to read news and RSS Feeds.
                </span>
              </div>
              <div class="home-feature1">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon04">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text04">
                  Works with all mail providers, including Google and Yahoo.
                </span>
              </div>
              <div class="home-feature2">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text05">
                  Over 2000, highly recommended customer reviews.
                </span>
              </div>
            </div>
          </div>
          <div class="home-image-container">
            <img
              alt="image"
              src="/playground_assets/hero%20image-1200w.png"
              class="home-image"
            />
          </div>
        </div>
      </div>
      <div class="home-section-one section-container">
        <div class="home-max-width1 max-content-container">
          <h2 class="home-text06 heading2">
            <span>
              Read
              <span v-html="raw17dh"></span>
            </span>
            <span class="home-text08">everything in one place</span>
            <span>and</span>
            <br />
            <span>keep up with important news</span>
          </h2>
          <div class="home-cards-container">
            <feature-card
              image_src="/playground_assets/stars-200h.png"
            ></feature-card>
            <feature-card
              text1="See how &gt;"
              heading="Follow favorite topics"
              image_src="/playground_assets/hearth-200h.png"
            ></feature-card>
            <feature-card
              text1="Learn more &gt;"
              heading="Read your emails"
              image_src="/playground_assets/mail-200h.png"
            ></feature-card>
            <feature-card
              text1="Learn more &gt;"
              heading="Read newspapers"
              image_src="/playground_assets/paper-200h.png"
            ></feature-card>
          </div>
        </div>
      </div>
      <div class="section-container">
        <div class="home-max-width2 max-content-container">
          <div class="home-image-container1">
            <img
              alt="image"
              src="/playground_assets/section-image1-1200w.png"
              class="home-image1"
            />
          </div>
          <div class="home-content-container1">
            <h1 class="home-text12 heading2">
              <span>
                Your favorite articles at your fingertips.
                <span v-html="raw2rqb"></span>
              </span>
              <span class="home-text14">Always.</span>
            </h1>
            <span class="home-text15 content-Light">
              <span>
                Amet minim mollit non deserunt ullamco est sit aliqua dolor do
                amet sint. Velit officia consequat duis enim velit mollit. Velit
                officia consequat duis enim velit mollit.
              </span>
              <br />
              <span>Lorem ipsum dolor sit amet.</span>
            </span>
          </div>
        </div>
      </div>
      <div class="section-container">
        <div class="home-max-width3 max-content-container">
          <div class="home-content-container2">
            <h1 class="home-text18 heading2">
              <span>
                The best content, handpicked for you.
                <span v-html="rawnm8n"></span>
              </span>
              <span class="home-text20">In the morning.</span>
            </h1>
            <span class="home-text21 content-Light">
              <span>
                Amet minim mollit non deserunt ullamco est sit aliqua dolor do
                amet sint. Velit officia consequat duis enim velit mollit. Velit
                officia consequat duis enim velit mollit.
              </span>
              <br />
              <span>Lorem ipsum dolor sit amet.</span>
            </span>
          </div>
          <div class="home-image-container2">
            <img
              alt="image"
              src="/playground_assets/section-image2-1200w.png"
              class="home-image2"
            />
          </div>
        </div>
      </div>
      <div class="home-section-four section-container">
        <div class="home-max-width4 max-content-container">
          <h2 class="home-text24 heading2">
            <span>People love Feedbox.</span>
            <br />
            <span class="home-text26">So would you.</span>
            <span class="home-text27"></span>
          </h2>
        </div>
        <div data-type="slider" class="home-slider">
          <app-slide></app-slide>
          <app-slide
            role="DESIGN DIRECTOR"
            Author="Bill Smith"
            image_src="/playground_assets/vector%202-700w.png"
            Testimonial='“Stunning app! I use it everyday since I discovered it and love it every since. It really makes newsreading a pleasure. I enjoy all the customization options available, super highly recommended!"'
            Testimonial2="Super highly recommended!”"
            rootClassName="slide-root-class-name"
          ></app-slide>
          <app-slide
            role="FREELANCE WRITER"
            Author="Julia Xang"
            image_src="/playground_assets/vector%202%20%5B2%5D-700w.png"
            Testimonial="“Feedbox is very easy to use and flexible! I especially like the pre-made templates that are accessible; they're extraordinary for monitoring a few feed sources and various RSS Feeds together.”"
            rootClassName="slide-root-class-name1"
          ></app-slide>
        </div>
      </div>
      <div class="section-container">
        <div class="home-max-width5 max-content-container">
          <div class="home-heading-container">
            <h2 class="home-text28 heading2">
              <span>If you love simplicity, you’ll</span>
              <br />
              <span>
                simply love
                <span v-html="raw4tzk"></span>
              </span>
              <span class="home-text31">Feedbox.</span>
            </h2>
            <span class="content-Light">
              <span>
                Go to App Store, install Feedbox and start changing your reading
                habits to
              </span>
              <span class="home-text34"></span>
              <span>day!</span>
            </span>
          </div>
          <div class="home-get-the-app">
            <img
              alt="image"
              src="/playground_assets/frame-1200w.png"
              class="home-image3"
            />
            <img
              alt="image"
              src="/playground_assets/frame%2034-200h.png"
              class="home-image4"
            />
          </div>
          <div class="home-cards-container1">
            <grid-card
              image_src="/playground_assets/vector%203-200h.png"
            ></grid-card>
            <grid-card
              text="Follow your friends"
              image_src="/playground_assets/vector%203%20%5B1%5D-200h.png"
            ></grid-card>
            <grid-card
              text="Declutter your life inbox"
              image_src="/playground_assets/vector%203%20%5B2%5D-200h.png"
            ></grid-card>
            <grid-card
              text="Less apps, more space"
              image_src="/playground_assets/vector%203%20%5B3%5D-200h.png"
            ></grid-card>
          </div>
        </div>
      </div>
      <div class="home-section-six section-container">
        <div class="home-max-width6 max-content-container">
          <div class="home-content-container3">
            <h1 class="home-text36 heading2">
              <span>Get started today.</span>
              <br />
              <span class="home-text38">Try free for 30 days.</span>
            </h1>
            <span class="home-text39 content-Light">
              Go to App Store, install Feedbox and start changing your reading
              habbits today!
            </span>
            <div class="home-input-container1">
              <div class="home-container2 input">
                <svg viewBox="0 0 804.5714285714286 1024" class="home-icon08">
                  <path
                    d="M804.571 708.571c0 20.571-9.143 60.571-17.714 79.429-12 28-44 46.286-69.714 60.571-33.714 18.286-68 29.143-106.286 29.143-53.143 0-101.143-21.714-149.714-39.429-34.857-12.571-68.571-28-100-47.429-97.143-60-214.286-177.143-274.286-274.286-19.429-31.429-34.857-65.143-47.429-100-17.714-48.571-39.429-96.571-39.429-149.714 0-38.286 10.857-72.571 29.143-106.286 14.286-25.714 32.571-57.714 60.571-69.714 18.857-8.571 58.857-17.714 79.429-17.714 4 0 8 0 12 1.714 12 4 24.571 32 30.286 43.429 18.286 32.571 36 65.714 54.857 97.714 9.143 14.857 26.286 33.143 26.286 50.857 0 34.857-103.429 85.714-103.429 116.571 0 15.429 14.286 35.429 22.286 49.143 57.714 104 129.714 176 233.714 233.714 13.714 8 33.714 22.286 49.143 22.286 30.857 0 81.714-103.429 116.571-103.429 17.714 0 36 17.143 50.857 26.286 32 18.857 65.143 36.571 97.714 54.857 11.429 5.714 39.429 18.286 43.429 30.286 1.714 4 1.714 8 1.714 12z"
                  ></path>
                </svg>
                <input
                  type="text"
                  placeholder="Your phone number..."
                  class="home-textinput1 input"
                />
              </div>
              <button class="home-button1 button-primary button">
                Get started
              </button>
            </div>
            <div class="home-features-container1">
              <div class="home-feature3">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon10">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text40">
                  Easiest way to read news and RSS Feeds.
                </span>
              </div>
              <div class="home-feature4">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text41">
                  Works with all mail providers, including Google and Yahoo.
                </span>
              </div>
              <div class="home-feature5">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon14">
                  <path
                    d="M733.714 419.429c0-9.714-3.429-19.429-10.286-26.286l-52-51.429c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-233.143 232.571-129.143-129.143c-6.857-6.857-16-10.857-25.714-10.857s-18.857 4-25.714 10.857l-52 51.429c-6.857 6.857-10.286 16.571-10.286 26.286s3.429 18.857 10.286 25.714l206.857 206.857c6.857 6.857 16.571 10.857 25.714 10.857 9.714 0 19.429-4 26.286-10.857l310.286-310.286c6.857-6.857 10.286-16 10.286-25.714zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text42">
                  Over 2000, highly recommended customer reviews.
                </span>
              </div>
            </div>
          </div>
          <div class="home-image-container3">
            <img
              alt="image"
              src="/playground_assets/group%2032-1200w.png"
              class="home-image5"
            />
          </div>
        </div>
      </div>
    </main>
    <app-footer></app-footer>
    <app-copyright></app-copyright>
  </div>
</template>

<script>
import AppNavbar from '../components/navbar'
import FeatureCard from '../components/feature-card'
import AppSlide from '../components/slide'
import GridCard from '../components/grid-card'
import AppFooter from '../components/footer'
import AppCopyright from '../components/copyright'

export default {
  name: 'Home',
  components: {
    AppNavbar,
    FeatureCard,
    AppSlide,
    GridCard,
    AppFooter,
    AppCopyright,
  },

  data() {
    return {
      rawx54s: ' ',
      rawno0p: ' ',
      raw17dh: ' ',
      raw2rqb: ' ',
      rawnm8n: ' ',
      raw4tzk: ' ',
    }
  },

  head: {
    title: 'Feedbox mobile app',
    meta: [
      {
        property: 'og:title',
        content: 'Feedbox mobile app',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
  background-color: var(--dl-color-backgrounds-gray);
}
.home-main {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-max-width {
  align-items: stretch;
}
.home-content-container {
  flex: 1;
  display: flex;
  min-width: 50%;
  align-items: flex-start;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  justify-content: center;
}
.home-text {
  width: 90%;
  margin-bottom: 42px;
}
.home-text02 {
  color: var(--dl-color-backgrounds-primary);
}
.home-input-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: row;
}
.home-container1 {
  width: 100%;
  height: 56px;
  display: flex;
  max-width: 376px;
  align-items: center;
  line-height: 1.5;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  margin-right: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-unit);
}
.home-icon {
  fill: var(--dl-color-grays-gray40);
  width: 20px;
  height: 20px;
}
.home-textinput {
  flex: 1;
  color: var(--dl-color-grays-gray40);
  border-width: 0px;
  padding-left: 12px;
  padding-right: 12px;
}
.home-button {
  display: flex;
  align-items: center;
  line-height: 1;
  padding-top: 20px;
  white-space: nowrap;
  padding-left: 32px;
  padding-right: 32px;
  padding-bottom: 20px;
  justify-content: center;
}
.home-features-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-feature {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  flex-direction: row;
}
.home-icon02 {
  fill: #62BF77;
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text03 {
  color: var(--dl-color-grays-gray60);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-feature1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  flex-direction: row;
}
.home-icon04 {
  fill: #62BF77;
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text04 {
  color: var(--dl-color-grays-gray60);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-feature2 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-icon06 {
  fill: #62BF77;
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text05 {
  color: var(--dl-color-grays-gray60);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-image-container {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-image {
  width: 100%;
  max-width: 589px;
  object-fit: cover;
  margin-left: 45px;
}
.home-section-one {
  border-color: rgba(33, 33, 33, 0.1);
  border-width: 1px;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.home-max-width1 {
  flex-direction: column;
}
.home-text06 {
  text-align: center;
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-text08 {
  color: var(--dl-color-backgrounds-primary);
}
.home-cards-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-max-width2 {
  flex-direction: row;
  justify-content: flex-start;
}
.home-image-container1 {
  flex: 1;
  margin-right: var(--dl-space-space-oneandhalfunits);
}
.home-image1 {
  width: 100%;
  max-width: 640px;
  object-fit: cover;
  margin-left: -100px;
}
.home-content-container1 {
  flex: 1;
  display: flex;
  max-width: 446px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text12 {
  margin-bottom: 24px;
}
.home-text14 {
  color: var(--dl-color-backgrounds-primary);
}
.home-text15 {
  color: var(--dl-color-grays-gray100);
}
.home-max-width3 {
  flex-direction: row;
  justify-content: flex-start;
}
.home-content-container2 {
  flex: 1;
  display: flex;
  max-width: 446px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text18 {
  margin-bottom: 24px;
}
.home-text20 {
  color: var(--dl-color-backgrounds-primary);
}
.home-text21 {
  color: var(--dl-color-grays-gray100);
}
.home-image-container2 {
  flex: 1;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-image2 {
  width: 100%;
  object-fit: cover;
  margin-left: 85px;
}
.home-section-four {
  padding-bottom: 0px;
}
.home-max-width4 {
  flex-direction: column;
}
.home-text24 {
  text-align: center;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-text26 {
  color: var(--dl-color-backgrounds-primary);
}
.home-text27 {
  color: transparent;
}
.home-slider {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  transition: 0.5s;
  align-items: stretch;
  flex-direction: row;
}
.home-max-width5 {
  flex-direction: column;
  justify-content: center;
}
.home-heading-container {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text28 {
  text-align: center;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text31 {
  color: var(--dl-color-backgrounds-primary);
}
.home-text34 {
  color: var(--dl-color-grays-gray100);
}
.home-get-the-app {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: row;
}
.home-image3 {
  width: 151px;
  object-fit: cover;
  margin-right: var(--dl-space-space-unit);
}
.home-image4 {
  width: 151px;
  object-fit: cover;
}
.home-cards-container1 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr;
}
.home-section-six {
  padding-top: var(--dl-space-space-threeunits);
  padding-bottom: 0px;
  background-color: var(--dl-color-backgrounds-primary);
}
.home-max-width6 {
  align-items: stretch;
}
.home-content-container3 {
  flex: 1;
  display: flex;
  min-width: 60%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text36 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text38 {
  color: var(--dl-color-grays-white100);
}
.home-text39 {
  color: var(--dl-color-grays-white80);
  margin-bottom: 36px;
}
.home-input-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-container2 {
  width: 100%;
  height: 56px;
  display: flex;
  max-width: 376px;
  align-items: center;
  line-height: 1.5;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  margin-right: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-unit);
}
.home-icon08 {
  fill: var(--dl-color-grays-gray40);
  width: 20px;
  height: 20px;
}
.home-textinput1 {
  flex: 1;
  color: var(--dl-color-grays-gray40);
  border-width: 0px;
  padding-left: 12px;
  padding-right: 12px;
}
.home-button1 {
  display: flex;
  transition: 0.3s;
  align-items: center;
  line-height: 1;
  padding-top: 20px;
  white-space: nowrap;
  padding-left: 32px;
  padding-right: 32px;
  padding-bottom: 20px;
  justify-content: center;
  background-color: var(--dl-color-grays-dark100);
}
.home-button1:hover {
  background-color: var(--dl-color-grays-white100);
}
.home-features-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-feature3 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  flex-direction: row;
}
.home-icon10 {
  fill: var(--dl-color-grays-white100);
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text40 {
  color: var(--dl-color-grays-white80);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-feature4 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  flex-direction: row;
}
.home-icon12 {
  fill: var(--dl-color-grays-white100);
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text41 {
  color: var(--dl-color-grays-white80);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-feature5 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-icon14 {
  fill: var(--dl-color-grays-white100);
  width: 17px;
  height: 17px;
  min-width: 17px;
  margin-right: 12px;
}
.home-text42 {
  color: var(--dl-color-grays-white80);
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
}
.home-image-container3 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-image5 {
  width: 100%;
  max-width: 589px;
  min-width: 550px;
  object-fit: contain;
}
@media(max-width: 991px) {
  .home-max-width {
    flex-direction: column;
  }
  .home-content-container {
    margin-bottom: 42px;
    padding-right: 0px;
  }
  .home-text {
    width: 100%;
  }
  .home-image {
    max-width: 100%;
    margin-left: 0px;
  }
  .home-image1 {
    max-width: 100%;
    margin-left: 0px;
  }
  .home-content-container1 {
    margin-bottom: 42px;
    padding-right: 0px;
  }
  .home-text12 {
    width: 100%;
  }
  .home-content-container2 {
    margin-bottom: 42px;
    padding-right: 0px;
  }
  .home-text18 {
    width: 100%;
  }
  .home-image2 {
    max-width: 100%;
    margin-left: 0px;
  }
  .home-max-width6 {
    flex-direction: column;
  }
  .home-text36 {
    width: 100%;
  }
  .home-image5 {
    max-width: 100%;
  }
}
@media(max-width: 767px) {
  .home-text06 {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-cards-container {
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .home-max-width2 {
    flex-direction: column;
  }
  .home-image-container1 {
    width: 100%;
    margin-right: 0px;
  }
  .home-image1 {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-content-container1 {
    max-width: 100%;
  }
  .home-max-width3 {
    flex-direction: column-reverse;
  }
  .home-content-container2 {
    max-width: 100%;
  }
  .home-image-container2 {
    width: 100%;
    margin-right: 0px;
  }
  .home-image2 {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text24 {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text28 {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-cards-container1 {
    grid-template-columns: 1fr;
  }
  .home-image5 {
    min-width: 100%;
  }
}
@media(max-width: 479px) {
  .home-input-container {
    flex-direction: column;
  }
  .home-container1 {
    max-width: 100%;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-cards-container {
    justify-content: center;
  }
  .home-input-container1 {
    flex-direction: column;
  }
  .home-container2 {
    max-width: 100%;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
