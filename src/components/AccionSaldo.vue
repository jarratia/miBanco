<template>
  <button @click="accion" :disabled="desactivar" class="btn btn-info">{{ texto }}</button> 
</template>

<script>
export default {
    props: {
        texto: String,
        desactivar: {
            type: Boolean,
            default: false
        }
    },
    methods: {
        accion() {
            this.$emit('accion')
        }
    }
}
</script>

<style>

</style>