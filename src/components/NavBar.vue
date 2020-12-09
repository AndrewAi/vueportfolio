<template>
    <div class="container">
        <div class="navBarLogo">
            <p>Andrew Irwin</p>
            <p>UX Designer</p>
        </div>
        <div class="navBarMenu">
            <p>About Me</p>
            <p>Resume</p>
            <p>Contact Me</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "NavBar",
}
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: row;
    max-width: 100%;
    /*margin: 20px;*/
}

.container div {
    border: solid grey 1px;
}

.navBarLogo {
    flex: 2;

    display: flex;
    flex-direction: column;
    padding-left: 50px;

    /*font-family: "Times New Roman", sans-serif;*/
    font-style: normal;
    font-weight: normal;
    font-size: 40px;
    line-height: 60px;
    text-align: center;
    text-decoration-line: underline;
}

.navBarMenu {
    flex: 1;

    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;

    font-family: Roboto, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 30px;
    line-height: 35px;
    color: #B58E58;
}
</style>
