<template>
  <q-layout view="lHh Lpr lFf bg-dark">
    <q-header class="bg-secondary">
      <q-toolbar
        :class="
          parseInt($q.screen.width) > 900
            ? 'flex flex-center pd-lr-prc-15 pd-tb-10 text-black bg-white'
            : 'flex flex-center pd-lr-10 pd-tb-10 text-black  bg-white'
        "
        style="background-color: transparent !important"
      >
        <nav_bar :changeMenuVisibility="changeMenuVisibility" />
      </q-toolbar>
    </q-header>

    <!-- <q-drawer v-model="leftDrawerOpen" bordered>
      <q-list>
        <q-item-label header> Essential Links </q-item-label>

        <EssentialLink
          v-for="link in essentialLinks"
          :key="link.title"
          v-bind="link"
        />
      </q-list>
    </q-drawer> -->

    <q-page-container class="bg-secondary">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";
import EssentialLink from "components/EssentialLink.vue";
import nav_bar from "components/nav_bar.vue";
import style_1 from "../css/style.css";
import style_2 from "../css/tailwind/tailwind-all.css";
import style_3 from "../css/tailwind/tailwind-all.min.css";
import style_4 from "../css/tailwind/tailwind-base.css";
import style_5 from "../css/tailwind/tailwind-base.min.css";
import style_6 from "../css/tailwind/tailwind-components.css";
import style_7 from "../css/tailwind/tailwind-components.min.css";
import style_8 from "../css/tailwind/tailwind-utilities.css";
import style_9 from "../css/tailwind/tailwind-utilities.min.css";

const linksList = [
  {
    title: "Docs",
    caption: "quasar.dev",
    icon: "school",
    link: "https://quasar.dev",
  },
];

export default defineComponent({
  name: "MainLayout",

  components: {
    // EssentialLink,
    nav_bar,
  },

  setup() {
    let leftDrawerOpen = ref(false);
    const active_style_1 = style_1;
    const active_style_2 = style_2;
    const active_style_3 = style_3;
    const active_style_4 = style_4;
    const active_style_5 = style_5;
    const active_style_6 = style_6;
    const active_style_7 = style_7;
    const active_style_8 = style_8;
    const active_style_9 = style_9;
    const changeMenuVisibility = (val) => {
      leftDrawerOpen.value = val;
    };
    return {
      essentialLinks: linksList,
      active_style_1,
      active_style_2,
      active_style_3,
      active_style_4,
      active_style_5,
      active_style_6,
      active_style_7,
      active_style_8,
      active_style_9,
      changeMenuVisibility,
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value;
      },
    };
  },
});
</script>
