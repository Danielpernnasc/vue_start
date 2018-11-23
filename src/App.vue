<template>
    <div class="container">
        <app-header></app-header>
                <hr>
             <div class="row">
                <service></service>
                <app-details></app-details>
            </div>
                <hr>
                <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './components/Shared/Header.vue';
    import Footer from './components/Shared/Footer.vue';
    import Service from './components/Server/Service.vue';
    import Details from './components/Server/Details.vue';

    export default {
        components: {
            'appHeader': Header,
             Service,
            'app-details': Details,
            'app-footer': Footer,
        }
    }
</script>

<style>

</style>
