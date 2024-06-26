<script setup></script>

<template>
  <main class="container">
    <div class="p-3"></div>
    <div class="big-padding grid border rounded ">
      <div class="p-3 g-col-12 g-col-md-9 ms-4">
        <h1 class="fs-4 mt-3 mb-0">Hello,</h1>
        <p class="fs-1 fw-semibold p-0 m-0">I'm <span class="fw-bold">Chris Bouwhuis</span></p>
        <p class="fs-2 m-0 text-highlight fw-medium">Full stack developer</p>
        <p class="fs-5">From Boekelo, The Netherlands</p>
        <router-link to="/contact" class="btn btn-primary hoverEffect">Hire me</router-link>
      </div>
      <div class="">
        <img
          alt="a picture of me"
          class=""
          src="../../public/img/ik-staand-smaller-removebg-preview.png"
        />
      </div>
    </div>
  </main>
</template>

<style scoped>
.big-padding {
  padding-top: 6rem;
}

.hoverEffect {
  transition: all 0.3s;
}

.hoverEffect:hover {
  transform: scale(1.1);
  background: linear-gradient(45deg, hsla(168, 85%, 52%, 0.5), hsla(263, 88%, 45%, 0.5) 100%);
  color: black;
}
</style>
