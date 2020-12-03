<template>
    <b-navbar fixed-top="true">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item href="#">
                <b-input placeholder="Search..."
                    type="search"
                    icon-pack="fas"
                    icon="search">
                </b-input>
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button" >
                        <span class="icon">
                        <i class="fas fa-shopping-bag"></i>
                        </span>
                    </a>
                    <a class="button" >
                        <span class="icon">
                        <i class="fas fa-user-circle"></i>
                        </span>
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>
<script>
  export default {
    name: 'Navbar'
  }
</script>
