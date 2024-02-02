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
                <li><a :href='url'>{{ text }}</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
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