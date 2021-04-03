<template>
  <div class="header">
    <div class="header__wrapper">
      <a class="header__logo" href="/">
        ComCon
      </a>

      <ul class="header__nav">
        <li class="header__nav-item">
          <router-link
              class="header__nav-link"
              active-class="header__nav-link--active"
              to="/"
          >
            Home
          </router-link>
        </li>

        <li class="header__nav-item">
          <router-link
              class="header__nav-link"
              active-class="header__nav-link--active"
              to="/about"
          >
            About
          </router-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class Header extends Vue {
}
</script>
<style lang="scss" src="./header.scss"></style>
