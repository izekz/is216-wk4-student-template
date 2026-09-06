<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  
    let message = "Choose your favourite fruit:"
    let [fruit1, fruit2, fruit3] = ['apple', 'orange', 'peach']
    
</script>

<template>
    {{ message }} 
   
    <label for=""> <input type="radio" name="fruit"> {{ fruit1 }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruit2 }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit3 }} </label> 
    
</template>

<style scoped>
</style>
