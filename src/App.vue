<template>
    <NavBar />
    <HeroImage />
    <Intro />
    <ProjectList />
    <ProjectOverview />
</template>

<script>
import NavBar from "./components/NavBar"
import HeroImage from "./components/HeroImage"
import Intro from "./components/Intro"
import ProjectList from "./components/ProjectList"
import ProjectOverview from "./components/ProjectOverview"

export default {
    name: "App",
    components: {
        ProjectOverview,
        ProjectList,
        NavBar,
        HeroImage,
        Intro,
    },
}
</script>

<style>
#app {
    font-family: Poppins,Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /*text-align: center;*/
    color: #2c3e50;
    padding: 20px;
}

* {
    margin: 0;
    padding: 0;
}
</style>
