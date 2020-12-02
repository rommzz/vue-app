<template>
    <b-navbar fixed-top="true">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="~@/assets/images/logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item href="#">
                <b-input placeholder="Search products"
                type="search"
                icon="magnify"
                icon-clickable
                @icon-click="searchIconClick">
            </b-input>
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button" >
                        <strong>
                            <div class="block">
                                <b-icon
                                    icon="basket"
                                ></b-icon>
                            </div>
                        </strong>
                    </a>
                    <a class="button is-light">
                        <div class="block">
                                <b-icon
                                    icon="account"
                                ></b-icon>
                            </div>
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
