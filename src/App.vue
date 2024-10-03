<template>
    <!--html-->
    <div class="app">
        <h1>hello!</h1>
        <Person/>
    </div>
</template>

<script lang="ts">
    //js and ts
    import Person from './components/Person.vue';
    export default{
        name: 'App', //組件名
        components:{Person} //註冊組件
    }
</script>

<style>
    /*樣式 */
    .app{
        background-color: #ddd;
        box-shadow: 0 0 10px;
        border-radius: 10px;
        padding: 20px;
    }
</style>