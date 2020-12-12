<template>
    <div class="container">
            <p class="projectsTitle">Projects</p>
        <div class="projectMiniList">
            <div>
                <img src="../assets/uxdilogo.png" class="projectImageMini">
                <p>Diploma Project: Fly UX Flight Booking App Design</p>
            </div>

            <div>
                <img src="../assets/uxdilogo.png" class="projectImageMini">
                <p>
                    Freelance Project: Pali Playcentre App Design & Development
                </p>
            </div>

            <div>
                <img src="../assets/uxdilogo.png" class="projectImageMini">
                <p>My Startup: DapDap Local Events App</p>
            </div>

            <div>
                <img src="../assets/uxdilogo.png" class="projectImageMini">
                <p>Drive Safe Road Safety App</p>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: "ProjectList",
}
</script>

<style scoped>
.container {
    border: solid gray 1px;
    /*max-width: 100%;*/

    display: flex;
    flex-direction: column;
}



.container div {
    border: solid gray 1px;
}

.projectsTitle {
    margin-left: 240px;
    margin-top: 25px;
    margin-bottom: 25px;
    /*padding-bottom: 60px;*/
    font-size: 40px;
    text-decoration: underline;
}

.projectMiniList {
    display: flex;
    /*height: 200px;*/
    margin-bottom: 100px;
}


.projectMiniList div {
    flex: 3;
    /*border: solid grey 1px;*/

    /*display: flex;*/
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.projectMiniTile {
    /*margin-bottom: 20px;*/
}

.projectImageMini {
    vertical-align: middle;
    width: 150px;
    height: 150px;
    border-radius: 10%;
    margin-bottom: 25px;
}


</style>
