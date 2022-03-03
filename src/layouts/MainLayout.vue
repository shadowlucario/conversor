<template>
  <q-layout>
    <div style="background-color:red;">
      <q-header elevated>
        <q-toolbar>
          <q-btn flat round dense icon="menu" class="q-mr-sm" />
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>

          <q-toolbar-title>Quasar Framework</q-toolbar-title>

          <q-btn flat round dense icon="whatshot" />
        </q-toolbar>
      </q-header>
      <q-page-container>
        <router-view />
      </q-page-container>
    </div>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'MainLayout',
});
</script>
