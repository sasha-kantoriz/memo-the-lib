<template>
    <div class="container-fluid">
        <div class="row">
            <div class="column">
                <h1>Memo library: book shelve</h1>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste nam deserunt expedita omnis neque harum maxime praesentium, totam impedit soluta, assumenda saepe sed culpa illum fuga pariatur. Ex, exercitationem laborum.
                </p>
                <a class="btn btn-primary" href="#">Amend</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "landing"
}
</script>

<style scoped lang="scss">
.container-fluid {
    height: 83vh;
    background: url("../assets/lib9.jpg");
    background-size: cover;
    display: flex;
    align-items: center;
}
.row {
    min-height: 25%;
    width: 100vw;
    background: transparentize(#000, 0.25);
    padding: 2.5em 0px;
}

.column {
    position: relative;
    font-family: monospace;
    color: whitesmoke;

    h1 {
        font-size: 1.6em;
        font-weight: bold;
    }
    p {
        font-size: 0.9em;
        padding: 5px;
    }
}
</style>
