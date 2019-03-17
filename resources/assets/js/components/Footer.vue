<template>
    <div class="main">



        <b-container class="grey-container" fluid>
            <b-row class="grey-row">
                <b-col>
                    <p class="title-text">BlazRobar.com</p>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
                        of type and scrambled it to make a type specimen book. It has survived not only five centuries,
                        but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised
                        in </p>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
                        of type and scrambled it to make a type specimen book. </p>
                </b-col>


                <b-col class="d-none d-md-block">

                    <p class="title-text">BlazRobar.com</p>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
                        of type and scrambled it to make a type specimen book. It has survived not only five centuries,
                        but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised
                        in </p>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
                        of type and scrambled it to make a type specimen book. </p>

                </b-col>
            </b-row>
        </b-container>



    </div>
</template>
<style lang="scss" scoped>

    @media (min-width: 640px) {

        .right-block {
            display: block;
        }

    }

    .grey-row{
        padding: 50px;
    }

    .grey-container{
        background-color: #ebebeb;
    }

    .title-text{
        color: #088ca5;
        font-size: 40px;
    }

</style>
<script>
    import axios from 'axios';


    export default {

    }
</script>