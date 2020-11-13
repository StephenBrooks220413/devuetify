<template>
<div class="about">
    <div class="jumbotron text-center">
        <h1>About Vue Development</h1>
        About Vue & Why Choose that as a framework
    </div>
    <br><br><br>
    <article class="container">
        <h4>According to altexsoft,</h4>
        While JavaScript is fully-fledged on its own, its ecosystem means much more than the language itself. Tools like frameworks make a developer’s life much easier by providing the basis for smoother development. If the language is considered the alphabet, the framework can be thought of as the phrasebook, enabling the developer to construct sentences and communicate.

        If you’ve been following JS framework market trends, you may know that the main contenders in the competition are React and Angular. The latest survey by Stack Overflow confirms React’s supremacy again this year, with Angular used more among professionals. But there is another contender on that list. <a href="https://www.altexsoft.com/blog/engineering/pros-and-cons-of-vue-js/" target="_blank">Read More.</a>
        <br><br>
        <img src="https://content.altexsoft.com/media/2019/09/word-image-14.png" width="100%" alt="comparison">
        <br><br>
        <small>pulled from <span style="color:blue;">https://www.altexsoft.com/blog/engineering/pros-and-cons-of-vue-js/</span></small>
    </article>
    <br><br><br>
    <p class="aboutText text-center">
        Fast and lightweight, easy to learn, easy to integrate current projects, easy to install or use cdn
    </p>
    <br><br><br>
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <p class="card-header text-center">Lightweight</p>
                    <div class="card-body text-center">
                        <i class="fas fa-running"></i>
                        <br><br>
                        over 300,000 developers use it
                        <br><br>
                        trusted by major companies too
                        <br><br>
                        <a type="btn" class="btn btn-info" href="mailto:stephen.brooks220413@gmail.com">MORE INFO</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <p class="card-header text-center">Easy Learning</p>
                    <div class="card-body text-center">
                        <i class="fas fa-graduation-cap"></i>
                        <br><br>
                        made with JavaScript libraries
                        <br><br>
                        Quick access to framework with cdn
                        <br><br>
                        <a type="btn" class="btn btn-info" href="mailto:stephen.brooks220413@gmail.com">MORE INFO</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <p class="card-header">Scaffolded to Build</p>
                    <div class="card-body text-center">
                        <i class="fab fa-phoenix-framework"></i>
                        <br><br>
                        Great framework to build on
                        <br><br>
                        Include any style you like
                        <br><br>
                        <a type="btn" class="btn btn-info" href="mailto:stephen.brooks220413@gmail.com">MORE INFO</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <br><br><br><br><br><br>
    <h1 class="display-4 text-center">Sites made with Vue.js</h1>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <h1 class="text-center"><a href="https://geteducation.link/?ref=madewithvuejs.com" target="_blank">Visit Site</a></h1>
                <img src="https://madewithnetwork.ams3.cdn.digitaloceanspaces.com/spatie-space-production/20224/education-link-2.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <h1 class="text-center"><a href="https://restaurantcolibri.ca/fr?ref=madewithvuejs.com" target="_blank">Visit Site</a></h1>
                <img src="https://madewithnetwork.ams3.cdn.digitaloceanspaces.com/spatie-space-production/12977/restaurant-colibri.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <h1 class="text-center"><a href="https://bowwe.com/?ref=madewithvuejs.com" target="_blank">Visit Site</a></h1>
                <img src="https://madewithnetwork.ams3.cdn.digitaloceanspaces.com/spatie-space-production/3520/bowwe.jpg" class="d-block w-100" alt="...">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
    <br><br><br><br><br><br>
</div>
</template>

<style scoped>
.aboutText {
    color: teal;
    text-shadow: 9px 10px 8px grey;
    font-size: 2em;
}

div.card-body i {
    font-size: 3.5em !important;
}
</style>
