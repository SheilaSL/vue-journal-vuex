<template>
  <div class="entry-title d-flex justify-content-between p-2">
      <div>
          <span class="text success fs-3 fw-bold">15</span>
          <span class="mx-1 fs-3">Julio</span>
          <span class="mx-2 fs-4 fw-light">2021, jueves</span>
      </div>
      <div>
        <div class="btn btn-danger mx-2">
            Borrar
        </div>
        <div class="btn btn-primary mx-2">
            Subir foto
        </div>
      </div>
  </div>
  <hr>
  <div class="d-flex flex-column px-3 h-75">
      <textarea></textarea>
  </div>

  <Fab texto="Guardar tarea" />

  <img src="" alt="entry-picture">
</template>

<script>
import {defineAsyncComponent} from 'vue'
export default {
    data() {
        return {
            texto: ''
        }
    },
    components: {
        Fab:  defineAsyncComponent(() => import('../components/Fab.vue'))
    }
}
</script>

<style>

</style>