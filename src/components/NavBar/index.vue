<!--
-------------------------------------------------
NavBar Component: index.vue
Desc: NavBar for the application
-------------------------------------------------
-->


<template>
    <nav class="navbar navbar-expand-lg navbar-dark weatherNavigation">
        <a class="navbar-brand" href="#">The Odin Project: Weather App</a>
        <button class="navbar-toggler weatherNavigationButton" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto weatherNavigationMenu">
                <li class="nav-item">
                    <a class="nav-link weatherNavigationMenuLink" href="https://salvillalon45.github.io/">About Salvador Villalon</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script src="./script.js"></script>

<style scoped src="./style.css"></style>
