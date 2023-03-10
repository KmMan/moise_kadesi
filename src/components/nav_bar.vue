<template>
  <q-item
    class="pd-n pd-lr-10 dh-100 bg-bty-1 bd-r-5 flex flex-center relative w-full flex flex-wrap items-center justify-between bg-gray-900 text-gray-200 shadow-lg navbar navbar-expand-lg navbar-light"
  >
    <q-item-label
      lines="1"
      class="text-xl text-white pr-2 font-semibold dw-30"
      href="#"
      >{{ "Profil".toUpperCase() }}</q-item-label
    >
    <q-space />
    <q-item-label lines="1" class="text-inter-bold text-h5 pd-r-20 text-green">
      Moise Kadesi
    </q-item-label>
    <q-avatar>
      <q-img src="../ic/profil-1.png" />
    </q-avatar>
  </q-item>
</template>
<script>
export default {
  props: {
    changeMenuVisibility: null,
  },
  setup() {
    return {};
  },
};
</script>
