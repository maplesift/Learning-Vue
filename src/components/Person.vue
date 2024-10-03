<template>
    <div class="person">
        <h2>姓名:{{name}}</h2>
        <h2>年齡:{{age}}</h2>
        <button @click="showTel">展示連絡電話</button>
    </div>
</template>

<script lang="ts">
    export default{
        name:'Person',
        data(){
            return{
                name:'amamya',
                age:'18',
                tel:'02-12345678',
            }
        },
        methods:{
            showTel(){
                alert(this.tel)
            }
        }
    }
</script>

<style scoped>
    .person{
        background-color: skyblue;
        box-shadow: 0 0 10px;
        border-radius: 10px;
        padding: 20px;
    }
</style>