<template>
  <section class="banner__area banner__padding">
    <div
      class="banner__bg tg-jarallax"
      style="background-image: url(/images/slider/banner_bg.jpg)"
    ></div>
    <div class="container custom-container">
      <div class="row justify-content-center">
        <div class="col-xl-8 col-lg-10">
          <div class="banner__content slider__content text-center">
            <h2 class="title wow bounceInLeft" data-wow-delay=".2s">
              steaming
            </h2>
            <p class="wow bounceInLeft" data-wow-delay=".4s">
              video games online
            </p>
            <div class="banner__btn wow bounceInLeft" data-wow-delay=".6s">
              <nuxt-link to="/contact" class="tg-btn-3 tg-svg mx-auto">
                <svg-animate-icon
                  icon="/images/icons/shape.svg"
                  id="svg-1"
                />
                <span>contact us</span>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
