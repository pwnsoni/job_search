<template>
    <div>
        <b-form-input v-model="text" placeholder="Type to search"></b-form-input>
        <div class="mt-2">Value: {{ text }}</div>
        <p> huhi</p>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            text: ''
        }
    }
}
</script>