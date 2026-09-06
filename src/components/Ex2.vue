<script setup>
    import { ref } from 'vue'

    // Add code here
    import me from '/assets/me.png'
    let width = 300
    let height = 200

    let imageAttr = {
        src : me,
        width : width,
        height : height
    }

</script>

<template>

    <!-- Add code here -->
   <img 
        v-bind:src="me"
        v-bind:width="width"
        v-bind:height="height"
   >

   <img v-bind="imageAttr">

</template>
