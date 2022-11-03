<template>
  <header class="primary-header flex">
    <div>
      <img src="../assets/shared/logo.svg" alt="space tourism logo" class="logo">
    </div>

    <nav>
      <ul class="primary-navigation underline-indicators flex">
        <li class="active">
          <router-link class="font-sans-cond uppercase text-white letter-spacing-2" to="/">
            <span>00</span> Home
          </router-link>
        </li>

        <li>
          <router-link class="font-sans-cond uppercase text-white letter-spacing-2" to="#">
            <span>01</span> Destination
          </router-link>
        </li>

        <li>
          <router-link class="font-sans-cond uppercase text-white letter-spacing-2" to="#">
            <span>02</span> Crew
          </router-link>
        </li>

        <li>
          <router-link class="font-sans-cond uppercase text-white letter-spacing-2" to="#">
            <span>03</span> Technology
          </router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>