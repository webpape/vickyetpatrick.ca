<template>
   <q-layout view="hhh Lpr fff">
      <!-- <q-header elevated>
         <q-toolbar>
            <q-btn flat dense round icon="menu" aria-label="Menu" />

            <q-toolbar-title> Quasar App </q-toolbar-title>

            <div>Quasar v{{ $q.version }}</div>
         </q-toolbar>
      </q-header> -->

      <q-page-container>
         <router-view />
      </q-page-container>
   </q-layout>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
   name: 'LayoutDefault',
   setup() {
      return {}
   }
})
</script>
