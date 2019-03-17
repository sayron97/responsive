<template>
    <div class="main">
        <div class="container-fluid">

            <div class="blue-block">
                <div class="blue-block-text">
                    <div>Awesome Free PSD</div>
                    <div>templates & Resourses</div>
                </div>
                <a class="main-link" href="#">www.BlazRobar.com</a>
            </div>
        </div>

        <b-container fluid>

            <b-row>
                <b-col class="purple-block" cols="8">I'm like the Robin Hood of PSD</b-col>
                <b-col class="pink-block" cols="4"> <span class="custom-arrow"> > </span> </b-col>
            </b-row>

        </b-container>

        <b-container fluid>
            <b-row>
                <b-col cols="12" md="4"><b-img src="img/1.png" fluid-grow alt="Responsive image" /></b-col>
                <b-col cols="12" md="4"><b-img src="img/2.png" fluid-grow alt="Responsive image" /></b-col>
                <b-col cols="12" md="4"><b-img src="img/3.png" fluid-grow alt="Responsive image" /></b-col>
            </b-row>
        </b-container>
    </div>
</template>
<style lang="scss" scoped>

    @media (min-width: 320px) {

        .blue-block-text {
            font-size: 26px;
        }

        .main-link {
            font-size: 14px;
        }

        .purple-block {
            font-size: 12px;
        }

        .pink-block{
            font-size: 36px;
        }


    }

    @media (min-width: 640px) {

        .blue-block-text {
            font-size: 42px;
        }

        .main-link {
            font-size: 26px;
        }

        .purple-block {
            font-size: 24px;
        }

        .pink-block{
            font-size: 52px;
        }

    }

    @media (min-width: 980px) {

        .blue-block-text {
            font-size: 72px;
        }

        .main-link {
            font-size: 42px;
        }

        .purple-block {
            font-size: 40px;
        }

        .pink-block{
            font-size: 82px;
        }

    }

    @media (min-width: 1024px) {

        .blue-block-text {
            font-size: 72px;
        }

        .main-link {
            font-size: 42px;
        }

        .purple-block {
            font-size: 40px;
        }

        .pink-block{
            font-size: 82px;
        }

    }

    .pink-block {
        background-color: #bc3183;
        color: white;
        padding-top: 7%;
        padding-bottom: 6%;
        padding-left: 7.804%;

        .custom-arrow{
            top: 30px;
        }
    }

    .purple-block {
        background-color: #27212c;
        color: #9282a0;
        padding-left: 7.804%;
        padding-top: 9.06%;
        padding-bottom: 9%;
    }

    .blue-block-text {
        color: #ffffff;
        margin-left: 7.804%;
        top: 34.78%;
    }

    .main-link {
        color: #a5d3dd;
        margin-left: 7.804%;
    }

    .blue-block {
        background-color: #0b9cb3;
        padding-top: 10%;
        padding-bottom: 10%;
    }

    .container-fluid {
        padding-right: 0;
        padding-left: 0;
    }

    .col-md-4 {
        padding-right: 0;
        padding-left: 0;
    }
</style>
<script>
    import axios from 'axios';


    export default {}
</script>