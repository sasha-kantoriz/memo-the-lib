<template>
    <nav class="navbar">
        <div class="container">
            <div class="navbar" id="navbarSuppotedContent">
                <ul class="nav nav-tabs ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#art">Art</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tech">Tech</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#amend_service">[+]</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

</template>

<script>
export default {
    name: 'navbar'
}
</script>

<style scoped>
.navbar {
    width: 100%;
    justify-content: center;
}
.nav-tabs {
    min-width: 80%;
}
li.nav-item {
    width: 33.3%;
}
.nav-link {
    min-height: 48px;
    color: black;
    font-weight: 500;
    font-size: 1.1em;
    font-family: monospace;
}
</style>