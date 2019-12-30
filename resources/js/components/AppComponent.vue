<template>
    <div>
        <h1>{{message}}</h1>
        <input type="text" v-model="message">
    </div>
</template>
<script>
export default{
    data(){
        return {
            message: "Hello, VueJS",
        }
    }
}
</script>
<style scoped></style>