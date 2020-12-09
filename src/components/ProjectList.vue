<template>
    <div class="container">
        <div>
            <p>Projects</p>
        </div>
        <div class="projectMiniList">
            <div>
                <div>Project Image</div>
                <p>Diploma Project: Fly UX Flight Booking App Design</p>
            </div>
            <div>
                <div>Project Image</div>
                <p>
                    Freelance Project: Pali Playcentre App Design & Development
                </p>
            </div>
            <div>
                <div>Project Image</div>
                <p>My Startup: DapDap Local Events App</p>
            </div>

            <div>
                <div>Project Image</div>
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
    max-width: 100%;
    height: 350px;

    display: flex;
    flex-direction: column;
}

.container div {
    border: solid gray 1px;
}

.projectMiniList {
    display: flex;
    height: 200px;
}

.projectMiniList div {
    flex: 3;
    border: solid grey 1px;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.projectMiniList div :nth-child(2) {
    max-width: 100px;
    text-align: left;
}
</style>
