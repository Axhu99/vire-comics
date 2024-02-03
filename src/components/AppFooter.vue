<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <section class="footer-top">
            <div class="container top-background">
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
            </div>
        </section>
        <section class="footer-bot">
            <div class="container">
                <div class="footer-sign">
                    <div class="button-sign">
                        <a class="button" href="">SIGN-UP NOW</a>
                    </div>
                    <div class="social">
                        <ul class="social-list">
                            <li><a href=""><img src="../../public/img/footer-facebook.png" alt=""></a></li>
                            <li><a href=""><img src="../../public/img/footer-twitter.png" alt=""></a></li>
                            <li><a href=""><img src="../../public/img/footer-youtube.png" alt=""></a></li>
                            <li><a href=""><img src="../../public/img/footer-pinterest.png" alt=""></a></li>
                            <li><a href=""><img src="../../public/img/footer-periscope.png" alt=""></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </footer>
</template>

<style>
.footer-top {
    background-image: url(../../public/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.top-background {
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

.footer-bot {
    background-color: #303030;
    padding: 40px 0;
}

.footer-sign {
    display: flex;
    justify-content: space-between;
}

.button-sign {
    display: flex;
    align-items: center;

}



.button {
    color: #fff;
    font-size: 1.3rem;
    border: 1px solid royalblue;
    padding: 20px 30px;
}

a.button {
    text-decoration: none;
}

.social {
    display: flex;
    align-items: center;
}

.social-list {
    display: flex;
    gap: 20px;
}

.social-list li {
    list-style-type: none;
}

.social-list img {
    width: 40px;
}
</style>