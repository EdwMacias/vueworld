<template>
<div>
    <form action="">
        <input type="text" v-model="inputText"/>
        <input type="checkbox" v-model="agree"/>Acepto los terminos y condiciones
        <select v-model="country">
            <option value="SP">Spain</option>
            <option value="UK">UK</option>
            <option value="FR">France</option>
            <option value="CA">Canada</option>

        </select>

<h3>{{ inputText }}</h3>
    </form>

</div>

</template>

<script lang="ts" setup>
    import {ref} from 'vue'
    let inputText = ref('')
    let agree = ref(false)
    let country = ref('CA')
</script>

<style scoped>

</style>