
<template>
    <div>
        <h3>九九re</h3>
        <button @click="count++">跳转备用网址{{count}}</button>
    </div>
    
</template>

<script>
export default {
    name:'',
    data(){
        return{
            count:0
        }
        
    }

}
</script>

<style>
    h3{
        color:brown;
    }
</style>