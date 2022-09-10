<template>
  <section class="intro">
    <div class="intro-content">
      <div class="svg-wrapper">
        <img
          class="three-line-wave-yellow"
          src="../assets/svg/three-line-wave-yellow.svg"
          alt="three-line-wave-yellow"
        />
      </div>
      <h1 class="intro-title">Shahriar <span>Eshraghi</span></h1>
      <p class="intro-description">Front-End Developer</p>
      <div class="svg-wrapper">
        <img src="../assets/svg/zig-zag-purple.svg" alt="zig-zag-purple" />
      </div>
      <div class="svg-wrapper">
        <img
          class="arrow-wave-yellow"
          src="../assets/svg/arrow-wave-yellow.svg"
          alt="arrow-wave-yellow"
        />
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped>
section.intro {
  @apply h-screen bg-cyan-400;
  div.intro-content {
    @apply h-screen flex gap-3 flex-col justify-center items-center;
    h1.intro-title {
      @apply flex flex-col items-center font-bold text-white text-5xl;
      span {
        @apply text-8xl;
      }
    }
    p.intro-description {
      @apply text-neutral-800 text-xl font-medium;
    }
    div.svg-wrapper {
      @apply w-7/12;
      img.arrow-wave-yellow,
      img.three-line-wave-yellow {
        @apply float-right;
      }
    }
  }
}
</style>
