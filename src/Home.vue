<template>
    <div>
        <p>Home status is : {{status}}</p>
        <button @click="changeStatus">Change</button>
        <p>
            <local-component></local-component>
        </p>
    </div>
</template>

<script>
import LocalComponent from './LocalComponent';
export default {
    components: {
        'local-component': LocalComponent,
    },
    data: function(){
        return{
            status: 'normal'
        }
    },
    methods: {
        changeStatus: function(){
            this.status = 'Alert'
        }
    }
}
</script>

<style lang="sass">

</style>