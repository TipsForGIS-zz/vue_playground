<template>
  <div>
    <p>Server status: {{status}}</p>
    <hr />
    <button v-on:click='change_status'>Change status</button>
  </div>
</template>
<script>
    export default{
        data(){
            return{
                status: 'Critical'
            }
        },
        methods:{
            change_status(){
                this.status = 'Normal';
            }
        }
    }
</script>