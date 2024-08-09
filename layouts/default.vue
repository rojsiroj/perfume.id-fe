<template>
  <div>
    <header>
      <ul v-if="false">
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
        <li v-if="!authenticated" class="loginBtn" style="float: right">
          <nuxt-link to="/login">Login</nuxt-link>
        </li>
      </ul>
    </header>
    <div class="mainContent">
      <slot />
    </div>
    <footer>
      <h1 v-if="false">Footer</h1>
    </footer>
  </div>
</template>
