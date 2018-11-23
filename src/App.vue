<template>
    <div class="container">
        <app-header></app-header>
                <hr>
             <div class="row">
                <app-service></app-service>
                <app-details></app-details>
            </div>
                <hr>
                <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './Header.vue';
    import Footer from './Footer.vue';
    import Service from './Service.vue';
    import Details from './Details.vue';

    export default {
        components: {
            'app-header': Header,
            'app-footer': Footer,
            'app-service': Service,
            'app-details': Details
        }
    }
</script>

<style>

</style>
