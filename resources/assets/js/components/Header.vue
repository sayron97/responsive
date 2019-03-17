<template>
    <div class="main">

            <b-navbar toggleable type="dark" variant="dark">
                <b-navbar-toggle target="nav_text_collapse" />
                <b-collapse is-nav id="nav_text_collapse">
                    <b-navbar-nav>
                        <b-nav-item class="links" href="#">PSD Websites</b-nav-item>
                        <b-nav-item class="links" href="#">UI Kits</b-nav-item>
                        <b-nav-item class="links" href="#">Premium psd files</b-nav-item>
                        <b-nav-item class="links" href="#">About</b-nav-item>
                        <b-nav-item class="links" href="#">Blog</b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </b-navbar>

    </div>
</template>
<style lang="scss" scoped>


    @media (min-width: 640px) {
        .navbar-dark{
            .navbar-nav{
                .nav-link {
                    display: block;
                }
            }
        }
    }

    .navbar-dark{
        .navbar-nav{
            .nav-link {
                font-size: 15px;
                font-family: 'Montserrat', sans-serif;
                color: rgb(255, 255, 255);
                line-height: 1.733;
                text-align: left;
            }
        }
    }

    .navbar{
        padding-top: 20px;
        padding-bottom: 20px;
    }


</style>
<script>
    import axios from 'axios';


    export default {

    }
</script>