<template>
    <div id="app">

        <!--Container-->
        <div class="container-fluid align-center info-landing text-center sec-pad-sm" style="overflow: hidden; position: relative;">
            <!--Logo-->
            <div class="logo-wrap">
                <a href="index-2.html">
                    <img class="brand-img" src="img/logo.png" alt="brand"/>
                    <span class="brand-text">Hound</span>
                </a>
            </div>
            <!--/Logo-->
            <!--main content-->
            <section class="intro-text sec-pad-top-xs padding-left-200 padding-right-200">
                <div class="ani-wrap">
                    <h1 class="animated ">Hound is a Bootstrap based Web UI Kit<br/> powered by Grunt, Bower and SCSS.</h1>
                </div>
                <div class="clearfix"></div>
                <div class="notify-btn main-menu margin-top-sm">
                    <a href="#link_proj" class="btn btn-info btn-rounded select-con md-trigger margin-top-85 margin-top-md-60 margin-top-sm-30">
                        <span class="mask"></span>
                        <span class="btn-label">
							<b>Demos</b>
						</span>
                    </a>
                    <a href="#" class="btn btn-success btn-rounded select-con md-trigger margin-top-85 margin-top-md-60 margin-top-sm-30  margin-left-15">
                        <span class="mask"></span>
                        <span class="btn-label">
							<b>Buy Now</b>
						</span>
                    </a>

                </div>
            </section>
            <!--VIDEO-1-->
            <video id="video_1" class="video full-height"  autoplay="autoplay" loop muted>
                <source src="video/demo.html" type="video/mp4">
                <source src="video/demo.webm" type="video/ogg">
                your browser does not support HTML5
            </video>
            <!--/VIDEO-1-->
            <div class="overlay-vid"></div>
        </div>

        <!--Technology Sec-->
        <div style="background:#f4f4f4;">
            <section id="tech_sec" class="container owl-carousel sec-pad-sm" >
                <div class="tech-carousel">
                    <img src="img/01-gruntt.png" alt="tech">
                    <img src="img/02-bower.png" alt="tech">
                    <img src="img/03-bootstrap.png" alt="tech">
                    <img src="img/04-sass.png" alt="tech">
                    <img src="img/05-html.png" alt="tech">
                    <img src="img/06-css.png" alt="tech">
                    <img src="img/07-jquery.png" alt="tech">
                    <img src="img/08-notejs.png" alt="tech">
                </div>
            </section>
        </div>
        <!--/Technology Sec-->


        <section class="container align-center text-left animated sec-pad-top sec-pad-bottom-sm about-sec" >
            <div class="row">
                <div class="col-lg-12">
                    <div class="about-icon-wrap padding-top-sm">
                        <h2 class="text-center margin-btm-lg">Why Hound ?</h2>
                        <div class="row">
                            <div class="col-sm-4  col-xs-12  margin-btm-lg">
                                <ul>
                                    <li><i class="fa  fa-bell-o"></i>Dark &amp; Light Demos</li>
                                    <li><i class="fa  fa-floppy-o"></i>Fullwidth &amp; Boxed Demos</li>
                                    <li><i class="fa   fa-list-ul"></i>Scrollable &amp; Fixed Sidebar</li>
                                    <li><i class="fa   fa-toggle-up"></i>Toggle Sidebar Menu</li>
                                    <li><i class="fa   fa-users"></i>User Profile Dashboard</li>
                                    <li><i class="fa  fa-shopping-cart"></i>Ecommerce Pages</li>
                                    <li><i class="fa  fa-building"></i>RTL Support</li>
                                    <li><i class="fa  fa-bars"></i>Mega Menu</li>
                                </ul>
                            </div>

                            <div class="col-sm-4  col-xs-12 margin-btm-lg margin-bottom-0">
                                <ul>
                                    <li><i class="fa  fa-mobile"></i>Special Mobile Menu</li>
                                    <li><i class="fa  fa-instagram"></i>Live Social Feeds – Twitter &amp; Instagram</li>
                                    <li><i class="fa  fa-th-large"></i>Lots of Widgets</li>
                                    <li><i class="fa  fa-bug"></i>Authentication Pages</li>
                                    <li><i class="fa  fa-meh-o"></i>Error Pages</li>
                                    <li><i class="fa  fa-archive"></i>Working Apps</li>
                                    <li><i class="fa  fa-support"></i>Easy to Customise</li>
                                    <li><i class="fa   fa-file"></i>File Manager</li>
                                </ul>
                            </div>
                            <div class="col-sm-4  col-xs-12 margin-btm-lg">
                                <ul>
                                    <li><i class="fa   fa-calendar"></i>Working Calendar App</li>
                                    <li><i class="fa   fa-mixcloud"></i>Working Weather App</li>
                                    <li><i class="fa    fa-wechat"></i>Chat App</li>
                                    <li><i class="fa   fa-inbox"></i>Mail App with Inbox Layout, Detail Email.</li>
                                    <li><i class="fa   fa-mobile-phone"></i>Contacts App with Cards &amp; List Option</li>
                                    <li><i class="fa   fa-tasks"></i>Task Manager / Todo List</li>
                                    <li><i class="fa   fa-thumbs-o-up"></i>More than you expected</li>
                                    <li><i class="fa    fa-ticket"></i>24/7 Support</li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </div>
            </div>
        </section>

        <div style="background:#f4f4f4;">
            <section id="link_proj" class="link-sec sec-pad-top sec-pad-bottom-sm container">
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="full-width-light/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/01.png" alt="">
                        </div>
                    </a>
                    <a href="full-width-light/index.html" target="_blank">
                        <h6>full width light</h6>
                    </a>
                </div>
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="full-width-dark/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/02.png" alt="">
                        </div>
                    </a>
                    <a href="full-width-dark/index.html" target="_blank">
                        <h6>full width dark</h6>
                    </a>
                </div>
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="fixed-width-light/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/03.png" alt="">
                        </div>
                    </a>
                    <a href="fixed-width-light/index.html" target="_blank">
                        <h6>fixed width light</h6>
                    </a>
                </div>
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="fixed-width-dark/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/04.png" alt="">
                        </div>
                    </a>
                    <a href="fixed-width-dark/index.html" target="_blank">
                        <h6>fixed width dark</h6>
                    </a>
                </div>
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="rtl-light/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/05.png" alt="">
                        </div>
                    </a>
                    <a href="rtl-light/index.html" target="_blank">
                        <h6>RTL Light Version</h6>
                    </a>
                </div>
                <div class="col-md-6  col-sm-12 text-center">
                    <a href="rtl-dark/index.html" target="_blank">
                        <div class="img-wrapper">
                            <img src="img/06.png" alt="">
                        </div>
                    </a>
                    <a href="rtl-dark/index.html" target="_blank">
                        <h6>RTL Dark Version</h6>
                    </a>
                </div>
            </section>
        </div>
        <!-- /Container -->

        <footer>
            <div class="footer-wrap text-center">
                <p>Hencework &copy; 2017.</p>
            </div>
        </footer>
    </div>
</template>

<script>

    export default {
        name: 'app',
    }
</script>

<style>
    @import "assets/css//owl.carousel.css";
    @import "assets/css//style.css";
</style>