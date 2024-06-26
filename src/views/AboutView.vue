<script setup></script>

<template>
  <div class="container pt-5 mt-5">
    <div class="d-flex flex-column align-items-center">
      <h1 class="text-decoration-underline p-2">Wie ben ik?</h1>
      <div
        class="row d-flex flex-column flex-xl-row justify-content-center align-items-center align-items-xl-start"
      >
        <div class="col-12 col-xl-8 order-1 order-xl-2 fs-4">
          <p class="">
            Mijn naam is Chris Bouwhuis en ik kom uit het prachtige
            <a
              href="https://www.google.com/maps/place/Boekelo,+7548+EH+Enschede/@52.2042139,6.7961489,16z/data=!3m1!4b1!4m6!3m5!1s0x47b8128b300211e1:0x77daef0fb862139e!8m2!3d52.2042146!4d6.8012987!16zL20vMGZqaHRo?authuser=0&entry=ttu"
            >
              dorp Boekelo</a
            >. Ik ben student aan het
            <a
              href="https://www.rocvantwente.nl/voor-scholieren/mbo-opleidingen/software-developer-bol-4.html"
            >
              ROC van Twente</a
            >, waar ik de versnelde opleiding Software Developer volg in
            <a
              href="https://www.google.com/maps/place/ROC+van+Twente+-+De+Gieterij/@52.2601902,6.7860334,17z/data=!4m15!1m8!3m7!1s0x47b811fd6515954d:0x3be3aa657b041408!2sGieterij,+7553+VZ+Hengelo!3b1!8m2!3d52.2601902!4d6.7886083!16s%2Fg%2F1tl4c2xc!3m5!1s0x47b80e02905554d3:0x2862a3d5ebd1ab56!8m2!3d52.2604764!4d6.7865537!16s%2Fg%2F1tq6cky9?authuser=0&entry=ttu"
              >De Gieterij in Hengelo</a
            >. In plaats van de reguliere vier jaar, rond ik deze opleiding af in drie jaar. Na mijn
            huidige studie wil ik graag verder studeren aan het HBO binnen de softwareontwikkeling.
          </p>
          <p class="">
            In mijn vrije tijd houd ik mij bezig met het maken van websites en webapplicaties. Ik
            gebruik de volgende talen, frameworks en technieken:
            <span class="fw-semibold">
              C#, php, javascript, python, laravel, filament, vue, alpinejs, livewire, tailwind,
              bootstrap en docker</span
            >. technieken en talen die ik nog wil leren zijn onder andere: react, dart, swift,
            kotlin, java, rust, Go en het gebruik van Bitlab runners en github actions voor CI/CD
            doeleinden.
          </p>
          <router-link to="/contact">Click hier als ik uw team kan versterken</router-link>
        </div>
        <div class="col-12 col-xl-4 order-2 order-xl-1">
          <img
            class="img-thumbnail shadow"
            src="../../public/img/ik-staand-smaller.jpg"
            alt="een foto waar sta"
          />
        </div>
      </div>
    </div>
  </div>
</template>
