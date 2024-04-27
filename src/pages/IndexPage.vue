<template>
  <div class="row q-pa-md">
    <q-label class="col-md-12 text-h3 q-mb-md">Formulario</q-label>
    <q-input outlined class="col-md-6"  label="nombre" :dense="dense" />
    <q-input outlined class="col-md-6"  label="Apellidos" :dense="dense" />
    <q-btn color="white" text-color="black" label="Standard" />

  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
