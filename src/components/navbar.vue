<template>
    <nav class="navbar navbar-dark">
        <div class="container">
            <div class="navbar" id="navbarSuppotedContent">
                <ul class="nav nav-tabs ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#art" data-toggle="tab">Art</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tech" data-toggle="tab">Techn</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#amend_service" data-toggle="tab">Amend Service</a>
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
    justify-content: right;
}

</style>