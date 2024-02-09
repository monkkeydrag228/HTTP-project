<template>
    <div class="card" v-for="person in people" :key="person" >
        {{ person }}
    </div>
</template>

<script>
export default{
    props:['people']
}

</script>

<style>
</style>