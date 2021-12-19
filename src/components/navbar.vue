<template>
    <nav>
        <ul class="nav">
            <div class="navbar-logo">
                <li>
                    <div class="navbar-brand">
                        <a class="navbar-brand" href="#">
                            <img class="header-logo" src="../assets/icon-of-books.png" alt="SPA site's logo" width="64" height="64">
                        </a>
                    </div>
                </li>
            </div>

            <div class="navbar-links">
                <li class="nav-item">
                    <a class="nav-link" href="#art">Art</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#tech">Tech</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#amend_service">[+]</a>
                </li>
            </div>

        </ul>
    </nav>

</template>

<script>
export default {
    name: 'navbar'
}
</script>

<style scoped>
nav {
    min-height: 100px;
}
.nav {
    display: flex;
    justify-content: space-between;
    /* align-items: center; */
}
.navbar-brand {
    display: flex;
    align-items: center;
    min-height: 100px;
    margin-left: 20px;
}
.navbar-links {
    align-items: center;
    display: flex;
    margin-right: 20px;
}
.nav-item a {
    min-height: 48px;
    font-size: 0.87em;
    font-family: monospace;
    font-weight: 400;
    color: rgb(61, 60, 60);
}
.nav-item a:hover {
    color: rgb(0, 0, 0);
    text-decoration: underline;
}

</style>