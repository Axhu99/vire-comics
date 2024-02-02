<script>
export default {
    name: 'AppMain',
    props: {
        comics: Array,
    }
}
</script>

<template>
    <main>
        <div class="container">
            <section class="title-current">
                <h1>current series</h1>
            </section>
            <div class="row">
                <div v-for="comic in comics" class="col">
                    <figure class="comic-img">
                        <img :src='comic.thumb' alt="">

                        <figcaption class="comic-title">
                            <h3>{{ comic.series }}</h3>
                        </figcaption>
                    </figure>
                </div>
            </div>
            <section class="loadmore-button">
                <button>load more</button>
            </section>
        </div>
    </main>
</template>

<style scoped>
main {
    background-color: #1C1C1C;
}

.title-current {
    background-color: #0282F9;
    display: inline-block;
    text-transform: uppercase;
    padding: 10px 20px;
}

.row {
    display: flex;
    flex-wrap: wrap;
    margin: 20px -10px;
}

.col {
    flex-basis: calc(100% / 6);
    padding: 0 10px;
}

.comic-img img {
    max-width: 100%;
}

.comic-title h3 {
    color: #fff;
    /* metterlo nel generics */
    text-transform: uppercase;
    padding: 20px 0;
    font-size: 0.8rem;
}

.loadmore-button {
    display: flex;
    justify-content: center;
    padding-bottom: 20px;
}

button {
    padding: 10px 60px;
    background-color: #0282F9;
    color: #fff;
    text-transform: uppercase;
    font-size: 1.2rem;
    font-weight: bold;
}
</style>