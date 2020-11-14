<template>
<!-- <div id="app"> -->
<v-app>
    <!-- <div id="nav"> -->
    <v-app-bar app>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">DevVuer</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <router-link class="nav-link nav-item active-link" to="/">Home</router-link>
                    <router-link class="nav-link nav-item" to="/about">About</router-link>
                    <router-link class="nav-link nav-item" to="/contact">Contact</router-link>
                    <router-link class="nav-link nav-item" to="/catalog">Catalog</router-link>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Follow Us
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <a class="dropdown-item" href="#" target="_blank">Facebook</a>
                            <a class="dropdown-item" href="#" target="_blank">Twitter</a>
                            <a class="dropdown-item" href="#" target="_blank">LinkedIn</a>
                        </div>
                    </li>
                </ul>
            </div>
        </nav>
    </v-app-bar>
    <v-main>
        <router-view />

    </v-main>
    <!-- </div> -->
    <v-footer app>
        <hr>
        <div class="footer">
            <p>
                &copy; 2020 - VueDeveloper {www.devVuer.com}
            </p>
        </div>
    </v-footer>
</v-app>
<!-- </div> -->
</template>

<style lang="scss">
@import './components/bootstrap.min.css';

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

#nav {
    padding: 30px;

    a {
        font-weight: bold;
        color: #2c3e50;

        &.router-link-exact-active {
            color: #42b983;
        }
    }
}

.footer {
    line-height: 50px;
    padding-left: 10%;
    padding-top: 10px;
}
</style>

<script>
import '../src/main';

export default {

}
</script>
