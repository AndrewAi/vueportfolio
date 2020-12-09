<template>
    <div class="container">
        <div class="introImage">Image</div>
        <div class="introName">
            <p>Hi, I'm Andrew!</p>
            <p>
                With my experience as an app Developer and UX Designer I can
                create solutions with a overall holistic approach.
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Intro",
}
</script>

<style scoped>
.container {
    border: solid gray 1px;
    max-width: 100%;
    height: 350px;

    display: flex;
    justify-content: center;
    align-items: center;
}

.container div {
    border: solid grey 1px;
}

.introImage {
    flex: 4;

    display: flex;
    justify-content: center;
    align-items: center;
}

.introName {
    flex: 8;
    /*max-width: 50%;*/
}

.introName p {
    max-width: 50%;
}
</style>
