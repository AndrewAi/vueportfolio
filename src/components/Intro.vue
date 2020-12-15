<template>
    <div class="container">
        <div class="introImage">
            <img src="../assets/myprofile2.png" class="profileImage">
        </div>

        <div class="introText">
            <h1>Hi, I'm Andrew!</h1>
            <p>
                With my experience as an app Developer and UX Designer I can
                create solutions with a overall holistic approach where the users is success always my
                top priority.
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
    padding-left: 100px;
}

/*.container div {*/
/*    border: solid grey 1px;*/
/*}*/

.introImage {
    flex: 4;

    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;
}

.introText {
    flex: 8;
    /*max-width: 50%;*/
}

.introText p {
    max-width: 50%;
    padding-top: 20px;
    font-size: 24px;
}

    .profileImage{
        vertical-align: middle;
        width: 250px;
        height: 250px;
        border-radius: 50%;
    }
</style>
