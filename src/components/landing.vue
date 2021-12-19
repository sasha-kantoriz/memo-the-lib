<template>
    <div class="container-fluid">
        <div class="row">
            <div class="column">
                <h1>Memo library: a book shelve</h1>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste nam deserunt expedita omnis neque harum maxime praesentium, totam impedit soluta, assumenda saepe sed culpa illum fuga pariatur. Ex, exercitationem laborum.
                </p>

                <div class="btn-group" role="group" aria-label="Basic outlined example">
                    <a type="button" class="btn btn-outline-light" href="#">New Book</a>
                    
                    <div class="btn-group" role="group" aria-label="Button group with nested dropdown">
                        <div class="btn-group" role="group">
                            <button id="btnGroupDrop1" type="button" class="btn btn-outline-light dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                                Library
                            </button>
                            <ul class="dropdown-menu" aria-labelledby="btnGroupDrop1">
                                <li><a class="dropdown-item" href="#">Artistic</a></li>
                                <li><a class="dropdown-item" href="#">Technical</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
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
    height: 87vh;
    @media screen and (min-width:250px) and (max-width:640px){
        background: url("../assets/lib3.jpg");
        background-size: cover;
    }
    @media screen and (min-width:641px) and (max-width:992px){
        background: url("../assets/lib12.jpg");
        background-size: cover;
    }
    @media screen and (min-width:993px){
        background: url("../assets/lib9.jpg");
        background-size: cover;
    }
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
    a {
        margin: 0 2px;
    }
}
</style>
