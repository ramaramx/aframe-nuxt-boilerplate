<template>
    <div>
        <h1> {{ message }} </h1>
    </div>
</template>

<script>
export default{
    name: 'Header',

    data(){
        return{
            message: 'This Footer'
        }
    }
}
</script>