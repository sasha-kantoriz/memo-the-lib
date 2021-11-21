<template>
    <div id="main">
        <div class="container-fluid">
        <div class="row">
            <div class="cover col-sm-12 col-md-12 col-lg-12">
                <h1>
                    Memo the Lib, book shelve 
                </h1>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vero ab voluptatem, cum totam maxime quae quam praesentium dicta! Explicabo laboriosam officia quam quis perspiciatis dolorem ducimus quas provident, libero repudiandae.
                </p>
                <a class="Amend btn btn-primary" href="#amend_service">Amend </a>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'landing'
}
</script>

<style scoped>
.container {
    max-width: 100%;
}
.row {

}
.cover {
       max-width: 100vw;
    min-height: 24%;
    max-height: 90%;
    background: rgb(0,0,0, 0.5);
    padding: 25px 0;
    position: absolute;
    bottom: 0; 
}
#main {
    /* position: relative; */
    background: url("../assets/lib12_1.jpg");
    height: 90vh;
    background-size: cover;
    background-position: center;
    padding: 280px 0 220px;
}
#main h1 {
    color: whitesmoke;
    font-size: 2.6em;
    font-weight: bold;
    /* text-transform: uppercase; */
}
#main p {
    font-size: 16px;
    color: whitesmoke;
    margin-top: 1em;
    padding-bottom: 25px;
}
/* #main .Amend {
    background: #718093;
    color: #fff;
    border-radius: 5px;
    padding: 10px 20px;
    text-decoration: none;
} */
</style>
