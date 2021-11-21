<template>
    <header class="header">
        <div class="container-fluid header_inner">
            <a class="navbar-brand header_title" href="#">
                <img class="d-inline-block header_logo" src="../assets/icon-of-books.png" alt="SPA site's logo" width="64" height="64">
                Memo, the Lib
            </a>
        </div>
    </header>
</template>

<script>
export default {
    name: 'logo'
}   
</script>

<style scoped>
.header {
    width: 100%;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.26);
}
.header_inner {
    min-height: 72px;
}
.header_title {
    display: inline-block;
    font-size: 1.5em;
    font-weight: 700;
    /* font-family:serif; */
    /* font-family: monospace; */
    font-family:initial;
    /* font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; */
    color: black;
}
</style>