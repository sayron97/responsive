<template>
    <div class="main">

        <header-nav></header-nav>

        <router-view></router-view>
        <images-block></images-block>
        <footer-text></footer-text>
    </div>
</template>
<style lang="scss" scoped>

    .container-fluid {
        padding-right: 0;
        padding-left: 0;
        &-grey{
            background-color: #eeeeee;
        }

    }
    .container-custom {
        width: 1200px;
        margin-right: auto;
        margin-left: auto;
        margin-bottom: 250px;
    }
    .grey-container {
        background-color: #eeeeee;
    }
    .container-middle{
        width: 1000px;
        margin-right: auto;
        margin-left: auto;
    }
    .container-middle-white{
        width: 1000px;
        margin-right: auto;
        margin-left: auto;
        background-color: white !important;
    }

</style>
<script>
    import MainList from '../components/MainList.vue'
    import Header from '../components/Header.vue'
    import Footer from '../components/Footer.vue'

    export default {
        components: {
            MainList: MainList,
            HeaderNav: Header,
            FooterText: Footer,

        },
        data() {
            return {};
        },
        computed: {}

    }
</script>