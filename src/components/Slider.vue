<template>
  <swiper
    :modules="modules"
    :pagination="{ clickable: true }"
    :autoplay="{
      delay: 2500,
    }"
    :loop="true"
    :breakpoints="{
      '640': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '768': {
        slidesPerView:2,
        spaceBetween: 40,
      },
      '1024': {
        slidesPerView: 2,
        spaceBetween: 50,
      },
    }"
    class="slider"
  >
    <swiper-slide>
      <div class="card mb-5">
        <div class="card-body">
          <div class="d-flex align-items-center">
            <div>
              <img
                alt="Image placeholder"
                src="https://preview.webpixels.io/purpose-website-ui-kit/assets/img/theme/light/team-2-800x800.jpg"
                class="avatar rounded-circle"
              />
            </div>
            <div class="text-container">
              <h5 class="h6 mb-0">Monroe Parker</h5>
              <small class="d-block text-muted">Apple</small>
            </div>
          </div>
          <p class="mt-4 lh-180">
            Amazing template! All-in-one, clean code, beautiful design, and really not
            hard to work with.Highly recommended for any kind on website.
          </p>
        </div>
      </div>
    </swiper-slide>
    <swiper-slide>
      <div class="card mb-5">
        <div class="card-body">
          <div class="d-flex align-items-center">
            <div>
              <img
                alt="Image placeholder"
                src="https://preview.webpixels.io/purpose-website-ui-kit/assets/img/theme/light/team-2-800x800.jpg"
                class="avatar rounded-circle"
              />
            </div>
            <div class="text-container">
              <h5 class="h6 mb-0">Monroe Parker</h5>
              <small class="d-block text-muted">Apple</small>
            </div>
          </div>
          <p class="mt-4 lh-180">
            Amazing template! All-in-one, clean code, beautiful design, and really not
            hard to work with.Highly recommended for any kind on website.
          </p>
        </div>
      </div>
    </swiper-slide>
    <swiper-slide>
      <div class="card mb-5">
        <div class="card-body">
          <div class="d-flex align-items-center">
            <div>
              <img
                alt="Image placeholder"
                src="https://preview.webpixels.io/purpose-website-ui-kit/assets/img/theme/light/team-2-800x800.jpg"
                class="avatar rounded-circle"
              />
            </div>
            <div class="text-container">
              <h5 class="h6 mb-0">Monroe Parker</h5>
              <small class="d-block text-muted">Apple</small>
            </div>
          </div>
          <p class="mt-4 lh-180">
            Amazing template! All-in-one, clean code, beautiful design, and really not
            hard to work with.Highly recommended for any kind on website.
          </p>
        </div>
      </div>
    </swiper-slide>
    <swiper-slide>
      <div class="card mb-5">
        <div class="card-body">
          <div class="d-flex align-items-center">
            <div>
              <img
                alt="Image placeholder"
                src="https://preview.webpixels.io/purpose-website-ui-kit/assets/img/theme/light/team-2-800x800.jpg"
                class="avatar rounded-circle"
              />
            </div>
            <div class="text-container">
              <h5 class="h6 mb-0">Monroe Parker</h5>
              <small class="d-block text-muted">Apple</small>
            </div>
          </div>
          <p class="mt-4 lh-180">
            Amazing template! All-in-one, clean code, beautiful design, and really not
            hard to work with.Highly recommended for any kind on website.
          </p>
        </div>
      </div>
    </swiper-slide>
  </swiper>
</template>
<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import {Pagination, Autoplay} from 'swiper/modules';
import "swiper/css";
import 'swiper/css/pagination';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination, Autoplay],
    };
  },
};
</script>

<style scoped>
.slider .card {
  margin-bottom: 30px;
  box-shadow: 0 0.75rem 1.5rem rgba(18, 38, 63, 0.03);
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 1px solid #eff2f7;
  border-radius: 0.375rem;
}

.swiper-slide .card {
  margin: 0;
}

.slider .card-body {
  flex: 1 1 auto;
  min-height: 1px;
  padding: 1.5rem;
  color: #8492a6;
}

.avatar {
  position: relative;
  color: #fff;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-size: 1rem;
  font-weight: 600;
  height: 50px;
  width: 50px;
  border-radius: 0.25rem;
}

.lh-180 {
  line-height: 1.8 !important;
}

.text-container{
  margin-left: 10px;
}
</style>
