<script>
export default {
    name: 'AppHeader',
    props: {
        navbarLinks: [],
    },
}
</script>

<template>
    <header>
        <nav class="navbar">
            <figure>
                <img src="../../public/img/dc-logo.png" alt="">
            </figure>
            <ul class="navbar-ul">
                <li v-for="navbarLink in navbarLinks"><a :href='navbarLink.url'>{{ navbarLink.text }}</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
.navbar {
    padding: 10px 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.navbar-ul {
    display: flex;
    gap: 10px;
}

li {
    list-style-type: none;
}

a {
    text-decoration: none;
}
</style>