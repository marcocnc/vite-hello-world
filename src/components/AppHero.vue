

<script>
export default {
    name: 'AppHero',
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <div>
        <img src="../assets/background.jpg" alt="background">
    </div>
</template>

<style scoped>
    div{
        width: 400px;
        height: 300px;
        border: 1px solid #fff;
    }

    div img{
        object-fit: cover;
        width: 100%;
        height: 100%;
    }
</style>