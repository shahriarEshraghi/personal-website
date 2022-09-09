<template>
  <section class="intro">
    <div>
      <h1>Shahriar <span>Eshraghi</span></h1>
      <p>Front-End Developer</p>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped>
section.intro {
  @apply h-screen bg-cyan-400;
  div {
    @apply h-screen flex gap-3 flex-col justify-center items-center;
    h1 {
      @apply flex flex-col items-center font-bold text-white text-5xl;
      span {
        @apply text-8xl;
      }
      p {
        @apply text-neutral-800 font-medium;
      }
    }
  }
}
</style>
