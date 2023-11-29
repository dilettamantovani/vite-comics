<script>
export default {
    name: 'Header',
    data() {
        return {
            navItems: [
                {
                    text: 'CHARACTERS',
                    url: '#'
                },
                {
                    text: 'COMICS',
                    url: '#'
                },
                {
                    text: 'MOVIES',
                    url: '#'
                },
                {
                    text: 'TV',
                    url: '#'
                },
                {
                    text: 'GAMES',
                    url: '#'
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#'
                },
                {
                    text: 'VIDEOS',
                    url: '#'
                },
                {
                    text: 'FANS',
                    url: '#'
                },
                {
                    text: 'NEWS',
                    url: '#'
                },
                {
                    text: 'SHOP',
                    url: '#'
                },
            ]
        }
    }
}

</script>

<template>
    <header class="d-flex align-items-center bg-light">
        <div class="row">
            <div class="col-3">
                <img class="my-2" src="../assets/img/dc-logo.png" alt="DC Logo">
            </div>

            <nav class="d-flex align-items-center col-9">
                <a class="fw-bold text-decoration-none text-dark px-3" v-for="item in navItems" href="item.url">{{
                    item.text }}</a>
            </nav>
        </div>
    </header>
</template>

<style scoped>
.row {
    margin: 0 auto;
}

img {
    width: 4.6rem;
}

a {
    font-size: 0.75rem;
}

a:hover {
    color: #0282F9 !important;
}
</style>
