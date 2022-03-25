<template>
    <h1>detail username</h1>
    <h2>Your username is {{idUsername}}</h2>
</template>

<script>
    export default {
        props: ['idUsername'],
        mounted() {
            console.log('idUsername', this.idUsername);
        }
    }
</script>