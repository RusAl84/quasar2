<template>
  <q-page class="flex flex-center">

<q-card>
  <q-card-section>
 <q-input outlined v-model="text" label="Outlined" />

  </q-card-section>
  <q-card-section>
    <q-card>
{{text}}
    </q-card>
  </q-card-section>
</q-card>



  </q-page>
</template>

<script>
import { defineComponent,ref } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  setup(){
    return {text:ref("")}
  }
})
</script>
