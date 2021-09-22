<template>
  <button class="btn btn-primary">{{texto}}</button>
</template>

<script>
export default {
    props: {
        texto: {
            type: String,
            default: 'Crear nueva tarea'
        } 
    }
}
</script>

<style lang="scss" scoped>
    
</style>