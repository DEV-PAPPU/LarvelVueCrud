<template>
    <router-view class="view one"></router-view>
</template>

<script>
export default {
    data() {
        return {
        }
    },

    mounted(){
        console.log('Main App Component ')
        console.log('router', this.router)

    }
}
</script>
