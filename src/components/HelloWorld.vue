<template>
<div class="hello">
    <br><br>
    <!--title-->
    <div class="jumbotron">
        <h1 class="display-4">Learn Your Style</h1>
    </div>
    <!---->
    <div class="bag">
        <h4>Your Cart</h4>
        <i id="basketImage" onclick="clickCart()" class="fas fa-shopping-bag"></i>
        <h2 id="itemCounter">0</h2>
        <p id="orderTotal"></p>
    </div>
    <br><br><br>
    <!--introduction-->
    <div class="container">
        <div class="row text-center">
            <div class="col-sm-4 col-md-4">
                <h3>Front End Code</h3>
                <ul>
                    <li>html, css, javascript</li>
                    <li>Material UI</li>
                    <li>Vue.js with Bootstrap</li>
                </ul>
                <img src="https://images.unsplash.com/photo-1472437774355-71ab6752b434?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1934&q=80" width="130" height="100" alt="frontend">
                <br><br><br>
                <div>
                    <button class="btn btn-outline-info" name="Espresso" onclick="addToCart(espresso)">Purchase Course</button>
                </div>
            </div>
            <div class="col-sm-4 col-md-4">
                <h3>Back End Code</h3>
                <ul>
                    <li>C# and JavaScript</li>
                    <li>SQL / MySQL DB</li>
                    <li>JSON & XML files</li>
                </ul>
                <img src="https://www.bing.com/th?id=AMMS_fe70d96bfd383ff776b6fa224f8dc299&w=110&h=110&c=7&rs=1&qlt=80&pcl=f9f9f9&cdv=1&dpr=1.5&pid=16.1" width="130" height="100" alt="backend">
                <br><br><br>
                <div>
                    <button class="btn btn-outline-info" name="Latte" onclick="addToCart(latte)">Purchase Course</button>
                </div>
            </div>
            <div class="col-sm-4 col-md-4">
                <h3>Fullstack Code</h3>
                <ul>
                    <li>asp.Net core</li>
                    <li>Angular framework</li>
                    <li>Vuetify with Vue.js</li>
                </ul>
                <img src="https://codeopinion.com/wp-content/uploads/2018/07/Bitmap-MEDIUM_ASP.NET-Core-Logo_2colors_Square_RGB.png" width="130" height="100" alt="fullstack">
                <br><br><br>
                <div>
                    <button class="btn btn-outline-info" name="Latte" onclick="addToCart(latte)">Purchase Course</button>
                </div>
            </div>
        </div>
    </div>
    <br><br><br><br><br>
    <div class="text-center">
        <router-view />
        <h5> Go To Checkout <router-link class="nav-link nav-item" to="/cart"><i class="fas fa-share-square"></i></router-link>
        </h5>
    </div>
    <br><br><br>
</div>
</template>

<script>
export default {
    name: "HelloWorld",
    props: {
        msg: String
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
h3 {
    margin: 40px 0 0;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}

.jumbotron {
    background-color: white !important;
}

i {
    font-size: 2.5em;
}

.bag {
    position: absolute;
    top: 150px;
    right: 40px;

}
</style>
