<script setup>
    import { ref } from 'vue'

    // Add code here
    const me_image = ref('/assets/me.png') 
    const width = ref('200')
    const height = ref('200')

    const imageAttr = ref({
        src : me,
        width : width,
        height : height
    })

</script>

<template>

    <!-- Add code here -->

   <img 
        v-bind:src="me_image"
        v-bind:width="width"
        v-bind:height="height"
   >

   <br>

   <img v-bind="imageAttr">

</template>
