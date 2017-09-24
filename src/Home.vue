<template>
    <div>
        <app-server-status v-for='server in 5'></app-server-status>
    </div>
</template>
<script>
    import server_status from './Server_status.vue'

    export default{
        components: {
            'app-server-status': server_status
        }
    }
</script>