<template>
    <div class="container">
        <div class="topSection">
            <div class="projectTitle">
                UX Design Diploma Project: Fly UX Flight Booking App Design
            </div>
            <div class="projectImage">Project Image</div>
        </div>
        <div class="bottomSection">
            <p class="projectSummary">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
                ad minim veniam, quis nostrud exercitation ullamco.
            </p>
            <p>See More Detail</p>
        </div>

    </div>
</template>

<script>
export default {
    name: "ProjectOverview",
}
</script>

<style scoped>
.container {
    border: solid gray 1px;
    height: 350px;
    display: flex;
    flex-direction: column;
}

.container div {
    border: solid gray 1px;
    flex: 1;
}

.topSection {
    display: flex;
}

.projectTitle {
    flex: 1;
    margin: auto;
    text-align: center;
}

.projectImage {
    flex: 1;
}
.bottomSection{
    display: flex;
    flex-direction: column;
}

.projectSummary {
    margin: auto;
    max-width: 500px;
}

.bottomSection :nth-child(2) {
    align-self: flex-end;
    margin-right: 20px;
    }

</style>
