<script setup>
import SubmitButton from '@/components/submit-button.vue'
</script>

<template>
  <div class="container">
    <div class="d-flex flex-column justify-content-center align-items-center">
      <h1 class="mt-5 mb-3">Contact</h1>
      <h2 class="text-center fs-3">
        Heb je vragen of wil je contact met mij opnemen? Dat kan!
        <span class="fw-bold">Vul het onderstaande formulier in</span> of stuur een berichtje naar
        een van mijn socialmedia accounts. Dan ik neem zo snel mogelijk contact met je op.
      </h2>
    </div>
    <form class="w-75 mx-auto mt-5">
      <div class="mb-3">
        <label for="name" class="form-label">Naam</label>
        <input
          type="text"
          class="form-control"
          id="name"
          placeholder="Vul hier je naam in"
          aria-describedby="nameHelp"
        />
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input
          type="email"
          class="form-control"
          id="email"
          placeholder="Vul hier je Email in"
          aria-describedby="emailHelp"
        />
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Bericht</label>
        <textarea
          class="form-control"
          id="message"
          placeholder="Plaats hier je bericht"
          rows="3"
        ></textarea>
      </div>
      <submit-button>Verstuur</submit-button>
    </form>
  </div>
</template>
