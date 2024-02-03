<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer class="bg-footer">
        <div class="container">
            <section class="footer-top">
                <!-- TODO rendere dinamica questa lista inventando un DATA con: -title -href -nome -->
                <div class="footer-list">
                    <ul>
                        <li class="li-title">Dc Comics</li>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                    <ul>
                        <li class="li-title">Shop</li>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC collectibles</a></li>
                    </ul>
                    <ul>
                        <li class="li-title">Dc</li>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy Policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPCS Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                    <ul>
                        <li class="li-title">Sites</li>
                        <li><a href="">Dc</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                    </ul>
                </div>

                <div class="logo">
                </div>

            </section>
            <section class="footer-bot">
                <div class="social">

                </div>
            </section>
        </div>
    </footer>
</template>

<style>
.bg-footer {
    background-image: url(../../public/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.footer-top {
    display: flex;
    height: 500px;
}

.footer-list {
    color: #fff;
    padding: 20px 0;

    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    flex-basis: 100%;
}

.footer-list ul {
    margin: 15px 0;
}

.footer-list .li-title {
    font-size: 1.8rem;
    font-weight: bolder;
    padding-bottom: 10px;
}

.footer-list li {
    list-style-type: none;
}

.footer-list a {
    text-decoration: none;
    color: white;
    line-height: 1.8rem;
    font-size: 1.2rem;
    opacity: 0.5;
}

.footer-list a:hover {
    opacity: 1;
}

.logo {
    display: flex;
    justify-content: flex-end;
    width: 130%;
    background-image: url(../../public/img/dc-logo-bg.png);
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: center;
}
</style>