<script>
import AppTitle from './AppTitle.vue';

export default {
    components:{
        AppTitle
    }
}
</script>

<template>
    
    <div>
        <AppTitle />
    </div>

</template>

<style scoped>
    div{
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        width: 100%;
        height:400px;
        background:url('../assets/space.webp');
        background-position: center;
        background-size:cover;
    }
</style>