<template>
  <q-page class="pd-n flex flex-center" style="overflow: hidden">
    <q-page :class="'flex dw-100'" style="height: 100%; overflow: hidden">
      <q-item class="pd-n" style="box-shadow: none; width: 100%">
        <q-card
          style="box-shadow: none; width: 100%"
          class="bd-r-0 bg-transparent"
        >
          <q-card-section style="height: 100%" class="pd-n flex flex-center">
            <q-scroll-area
              :thumb-style="thumbStyle"
              :bar-style="barStyle"
              class=""
              style="height: 100%; width: 100%"
            >
              <q-list class="dw-100">
                <q-item-label
                  class="pd-10 dw-100 text-center text-inter-bold text-accent"
                >
                  PROFIL PROFESSIONEL
                </q-item-label>
                <q-item class="dw-100 flex flex-center">
                  <q-img
                    width="200px"
                    height="200px"
                    class="bd-r-50 shadow-10"
                    src="../ic/profil-1.png"
                  />
                </q-item>
                <q-item-label
                  class="pd-20 dw-100 text-center text-h6 text-inter-bold text-white"
                >
                  MOISE KADESI
                </q-item-label>
                <q-item class="dw-100 flex flex-center">
                  <section class="gradient-form flex flex-center">
                    <div class="container py-0 px-0">
                      <div
                        :class="
                          parseInt($q.screen.width) > 900
                            ? 'flex justify-center px-40 items-center flex-wrap g-6 '
                            : 'flex justify-center items-center flex-wrap g-6 '
                        "
                      >
                        <div
                          style="width: 100% !important"
                          :class="
                            parseInt($q.screen.width) > 900
                              ? 'xl:w-10/12'
                              : 'dw-100'
                          "
                        >
                          <div class="block bg-static-trans-1 rounded-lg">
                            <div class="lg:flex lg:flex-wrap g-0">
                              <div class="lg:w-6/12 px-4 md:px-10">
                                <div
                                  class="px-4 py-4 md:p-2 lg:rounded md:mx-1 md:my-1"
                                >
                                  <div class="text-center">
                                    <h4 class="font-semibold mb-4">
                                      <q-item-label
                                        class="text-h6 text-bold text-accent pd-b-5 mr-b-5"
                                      >
                                        {{ "Production Manager" }}
                                      </q-item-label>
                                    </h4>
                                    <q-item
                                      dense
                                      class="pd-tb-10 flex flex-center dw-100"
                                    >
                                      <q-img
                                        height="80px"
                                        width="100px"
                                        src="../ic/logo.png"
                                        alt="logo"
                                      />
                                    </q-item>
                                    <h4 class="text-xl mt-1">
                                      <span
                                        class="text-inter-bold text-green"
                                        >{{ "243Digit" }}</span
                                      >
                                      <br />
                                    </h4>
                                    <h4 class="mb-5 text-bold text-white">
                                      <span>work is your only freedom</span>
                                    </h4>
                                  </div>
                                  <form>
                                    <!-- <p class="mb-4">Please login to your account</p> -->
                                    <div class="mb-4">
                                      <q-item-label
                                        class="text-center dw-100 h4 text-accent"
                                      >
                                        <span class="text-white text-bold"
                                          >243Digit</span
                                        >
                                        est une organisation digitale qui, comme
                                        son nom l'indique, œuvre dans le secteur
                                        numérique. Nous fournissons une gamme
                                        diversifiée des services numériques dans
                                        l'étude comme dans la mise en œuvre.
                                      </q-item-label>
                                    </div>
                                  </form>
                                </div>
                              </div>

                              <div
                                class="lg:w-6/12 flex items-center lg:rounded pd-10"
                                style=""
                              >
                                <div
                                  class="bd bd-static-trans-2 bg-static-trans-1 mr-lr-10 text-white px-4 dh-100 py-6 md:p-10 bd-r-5 md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold mb-4">
                                    <q-item-label
                                      lines="1"
                                      class="text-h5 text-bold pd-b-5 mr-b-5"
                                    >
                                      {{ "Profil & Description" }}
                                    </q-item-label>
                                  </h4>
                                  <p class="text-sm pd-b-20 mr-b-20 dh-40">
                                    <q-item-label lines="10" class="h4">
                                      <span class=""
                                        >Concepteur des systèmes d'information
                                        dans les normes de la nouvelle
                                        technologie de l'information et de la
                                        communication.</span
                                      >
                                      <br />
                                      <br />
                                      <span class="mr-b-10">Domaines :</span
                                      ><br />
                                      <br />
                                      <span> -> Réseaux informatique;</span>
                                      <br />
                                      <span> -> Développement logiciel</span>
                                      <br />
                                      <span> -> Maintenance informatique</span>
                                      <br />
                                      <span> -> Remote Support</span>
                                    </q-item-label>
                                  </p>
                                  <h4 class="text-xl font-semibold mb-4">
                                    <q-item-label
                                      lines="1"
                                      class="text-h5 text-bold pd-b-5 mr-b-5"
                                    >
                                      {{ "Adresse & Contacts" }}
                                    </q-item-label>
                                  </h4>
                                  <h4 class="font-semibold pd-l-10 mb-2">
                                    <q-item-label lines="1">
                                      <q-icon size="20px" name="house" /> :
                                      {{ "Bukavu - DRC" }}
                                    </q-item-label>
                                  </h4>
                                  <h4 class="font-semibold pd-l-10 mb-2">
                                    <q-item-label lines="1">
                                      <q-icon size="20px" name="email" /> :
                                      {{ "moise.kadesi.manasse@gmail.com" }}
                                    </q-item-label>
                                  </h4>
                                  <h4 class="font-semibold pd-l-10 mb-2">
                                    <q-item-label lines="1">
                                      <q-icon size="20px" name="email" /> :
                                      {{ "243digit.contact.pro@gmail.com" }}
                                    </q-item-label>
                                  </h4>
                                  <h4 class="font-semibold pd-l-10 mb-6">
                                    <q-item-label lines="1">
                                      <q-icon size="20px" name="phone" /> :
                                      {{ "+(243) 998 358 238" }}
                                    </q-item-label>
                                  </h4>
                                </div>
                              </div>

                              <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-adapt px-4 py-6 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold">
                                    <q-item-label
                                      lines="1"
                                      class="text-h5 text-bold text-accent text-white"
                                    >
                                      Nos produits & Services
                                    </q-item-label>
                                  </h4>
                                  <h4 class="text-xl font-semibold pd-t-20">
                                    <q-item-label
                                      class="h4 text-bold text-accent"
                                    >
                                      En dehors des services sur mesure que nous
                                      offrons à nos clients, Nous fournissons
                                      aussi des produits standards et services
                                      de qualité pour une bonne gestion des vos
                                      différentes activités.
                                    </q-item-label>
                                  </h4>
                                  <h4
                                    class="text-xl font-semibold pd-t-20 mr-t-20"
                                  >
                                    <q-item-label
                                      lines="1"
                                      class="text-h5 text-bold text-accent pd-b-20"
                                    >
                                      <q-icon
                                        size="40px"
                                        name="category"
                                        color="white"
                                        class="mr-r-10"
                                      />
                                      <q-space />
                                    </q-item-label>
                                  </h4>
                                  <h4 class="text-xl font-semibold">
                                    <q-item-label
                                      lines="1"
                                      class="text-h4 text-bold text-accent"
                                    >
                                      Produits
                                      <q-space />
                                    </q-item-label>
                                  </h4>
                                  <h4 class="text-xl font-semibold pd-t-20">
                                    <q-item-label
                                      lines="1"
                                      class="text-h5 text-bold text-accent text-white"
                                    >
                                      1. Manager
                                    </q-item-label>
                                  </h4>
                                  <h4 class="text-xl font-semibold pd-t-20">
                                    <q-item-label
                                      class="h4 text-bold text-accent"
                                    >
                                      Manager est un logiciel multi modules qui
                                      permet une gestion parfaite des vos
                                      activités dans différents domaines. Un
                                      grand nombre de ses modules sont
                                      disponibles et fonctionnels. Pour plus
                                      d'informations vous pouvez nous contacter
                                      par les contacts disponibles plus haut.
                                    </q-item-label>
                                  </h4>
                                </div>
                              </div>

                              <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-white px-0 py-0 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <q-list
                                    :class="
                                      parseInt($q.screen.width) > 900
                                        ? 'dw-100 flex flex-center pd-lr-20'
                                        : 'dw-100 flex flex-center pd-lr-20'
                                    "
                                  >
                                    <q-item
                                      v-memo="[]"
                                      v-for="(s, si) in managerSystemServices"
                                      :key="si"
                                      dense
                                      :class="
                                        (parseInt($q.screen.width) > 900
                                          ? ' dw-30'
                                          : '') +
                                        ' ' +
                                        (parseInt($q.screen.width) <= 900
                                          ? (parseInt($q.screen.width) >= 700 &&
                                            parseInt($q.screen.width) <= 900
                                              ? 'dw-30'
                                              : '') +
                                            ' ' +
                                            (parseInt($q.screen.width) >= 500 &&
                                            parseInt($q.screen.width) < 700
                                              ? 'dw-50'
                                              : '') +
                                            ' ' +
                                            (parseInt($q.screen.width) >= 0 &&
                                            parseInt($q.screen.width) < 500
                                              ? 'dw-100'
                                              : '') +
                                            ' '
                                          : '') +
                                        ' ' +
                                        'bg-static-trans-1 bd bd-static-trans-2 bd-r-5 pn-n pd-5 mr-lr-10 mr-tb-10'
                                      "
                                    >
                                      <q-list class="dw-100">
                                        <q-item
                                          dense
                                          :class="'pd-n bd-b bd-static-trans-5'"
                                        >
                                          <q-item-label
                                            lines="1"
                                            class="text-inter-bold text-white pd-lr-5 dw-100 text-center"
                                          >
                                            {{ s.label.toUpperCase() }}
                                          </q-item-label>
                                          <q-tooltip
                                            class="bg-secondary bd bd-static-trans-5 text-white"
                                          >
                                            {{ s.label.toUpperCase() }}
                                          </q-tooltip>
                                        </q-item>
                                        <q-item>
                                          <q-item-label
                                            lines="1"
                                            class="text-white mr-tb-10 dw-100 text-center text-inter-bold"
                                          >
                                            {{ "MODULE " + (si + 1) }}
                                          </q-item-label>
                                        </q-item>

                                        <q-item>
                                          <q-item-label
                                            lines="4"
                                            class="text-white h4 mr-tb-10 dw-100 text-center"
                                          >
                                            {{ s.details }}
                                          </q-item-label>
                                          <q-tooltip
                                            class="bg-secondary h5 bd bd-static-trans-5 text-white dmxw-50"
                                          >
                                            {{ s.details }}
                                          </q-tooltip>
                                        </q-item>

                                        <q-item
                                          class="flex flex-center pd-tb-10 mr-tb-10"
                                        >
                                          <q-btn
                                            flat
                                            :class="
                                              'bd bd-static-trans-5 text-' +
                                              ramdom_colors_gen[si]
                                            "
                                            :label="'Apply'"
                                          />
                                        </q-item>
                                      </q-list>
                                    </q-item>
                                  </q-list>
                                </div>
                              </div>
                              <!-- <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-adapt px-4 py-6 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold pd-t-20">
                                        <q-item-label
                                          lines="1"
                                          class="text-h5 text-bold text-accent text-white"
                                        >
                                          2. Univ Manager
                                        </q-item-label>
                                  </h4>
                                </div>
                              </div>
                              <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-adapt px-4 py-6 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold pd-t-20">
                                        <q-item-label
                                          lines="1"
                                          class="text-h5 text-bold text-accent text-white"
                                        >
                                          3. Guest Auth
                                        </q-item-label>
                                  </h4>
                                </div>
                              </div> -->
                              <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-adapt px-4 py-6 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold pd-tb-20">
                                    <q-item-label
                                      lines="1"
                                      class="text-h4 text-bold text-accent"
                                    >
                                      Services
                                    </q-item-label>
                                  </h4>

                                  <h4 class="text-xl font-semibold pd-tb-20">
                                    <q-item-label
                                      class="text-h6 text-bold text-accent text-white"
                                    >
                                      1. Conception & mise en place de :
                                    </q-item-label>
                                  </h4>
                                  <p class="font-semibold">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">1.1</span>.
                                      Systemes d'informations informatique
                                    </q-item-label>
                                  </p>
                                  <p class="font-semibold pd-tb-10">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">1.2</span
                                      >.Conception & mise en place des reseaux
                                    </q-item-label>
                                  </p>

                                  <h4 class="text-xl font-semibold pd-tb-20">
                                    <q-item-label
                                      class="text-h6 text-bold text-accent text-white"
                                    >
                                      2. Developpement :
                                    </q-item-label>
                                  </h4>
                                  <p class="font-semibold">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">2.1</span>.
                                      Developpement Web
                                    </q-item-label>
                                  </p>
                                  <p class="font-semibold pd-t-10">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">2.2</span>.
                                      Developpement Mobile
                                    </q-item-label>
                                  </p>
                                  <p class="font-semibold pd-t-10">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">2.3</span>.
                                      Developpement Desktop
                                    </q-item-label>
                                  </p>
                                  <h4
                                    class="text-xl font-semibold pd-t-20 pd-tb-20"
                                  >
                                    <q-item-label
                                      class="text-h6 text-bold text-accent text-white"
                                    >
                                      3. Maintenance, etc :
                                    </q-item-label>
                                  </h4>
                                  <p class="font-semibold">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">3.1</span>. Audit
                                      informatique;
                                    </q-item-label>
                                  </p>
                                  <p class="font-semibold pd-tb-10">
                                    <q-item-label class="text-bold text-accent">
                                      <span class="text-green">3.2</span>.
                                      Maintenance informatique.
                                    </q-item-label>
                                  </p>
                                </div>
                              </div>
                              <!-- <div class="flex items-center dw-100" style="">
                                <div
                                  class="dw-100 text-adapt px-4 py-6 md:p-10 lg:rounded md:mx-1 md:my-1"
                                >
                                  <h4 class="text-xl font-semibold">
                                    <q-item-label
                                      lines="1"
                                      class="text-h4 text-bold text-accent"
                                    >
                                    Réalisations
                                      <q-space />
                                    </q-item-label>
                                  </h4>
                                <q-list class="dw-100 flex">
                                  <q-item dense :class="
                                  (parseInt($q.screen.width) > 900 ? '':'')+' '+
                                  ('pd-n')
                                  ">
                                    <q-list>
                                      <q-img height="100px" width="150px" class="bd-r-10 bg-static-trans-1" src="../ic/pelections.jpg">
                                        <q-list class="absolute-bottom dw-100 pd-n">
                                          <q-item-label class="dw-100 text-inter-bold">
                                            Projet ELections
                                          </q-item-label>
                                          <q-item-label class="dw-100 text-bold">
                                            Julizha
                                          </q-item-label>
                                        </q-list>
                                      </q-img>
                                    </q-list>
                                  </q-item>
                                  <q-item dense :class="
                                  (parseInt($q.screen.width) > 900 ? 'pd-l-10':'')+' '+
                                  ('pd-n')
                                  ">
                                    <q-list>
                                      <q-img height="100px" width="120px" class="bd-r-10 bg-static-trans-1" src="../ic/kinigi.png">
                                        <q-list class="absolute-bottom dw-100 pd-n">
                                          <q-item-label class="dw-100 text-inter-bold">
                                            Kinigi App
                                          </q-item-label>
                                          <q-item-label class="dw-100 text-bold">
                                            Kinigi Ltd
                                          </q-item-label>
                                        </q-list>
                                      </q-img>
                                    </q-list>
                                  </q-item>

                                  <q-item dense :class="
                                  (parseInt($q.screen.width) > 900 ? 'pd-l-10':'')+' '+
                                  ('pd-n')
                                  ">
                                    <q-list>
                                      <q-img height="100px" width="250px" class="bd-r-10 bg-white" src="../ic/cipreasbl.png">
                                        <q-list class="absolute-bottom dw-100 pd-n">
                                          <q-item-label class="dw-100 text-inter-bold">
                                            Website
                                          </q-item-label>
                                          <q-item-label class="dw-100 text-bold">
                                            Cipre Education
                                          </q-item-label>
                                        </q-list>
                                      </q-img>
                                    </q-list>
                                  </q-item>
                                </q-list>
                                </div>
                              </div> -->
                              <div class="flex items-center dw-100" style="">
                                <div
                                  class="bg-primary dw-100 text-white px-4 py-6 md:p-4 bd-r-5 md:mx-1 md:my-1"
                                >
                                  <p class="text-sm dw-100">
                                    <q-item-label
                                      class="dw-100 text-right flex flex-center"
                                    >
                                      <!-- <q-img
                                        width="40px"
                                        height="30px"
                                        class="mr-r-10"
                                        src="../ic/logo.png"
                                      /> -->
                                      <span
                                        class="text-h5 text-bold text-white"
                                      >
                                        243Digit
                                      </span>
                                      <q-space />
                                      <span
                                        class="text-green text-bold text-inter-bold"
                                      >
                                        work is your only freedom
                                      </span>
                                    </q-item-label>
                                  </p>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </section>
                </q-item>
              </q-list>
            </q-scroll-area>
          </q-card-section>
        </q-card>
      </q-item>
    </q-page>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import { useQuasar } from "quasar";
export default defineComponent({
  name: "IndexPage",
  setup() {
    const $q = useQuasar();
    var ramdom_colors = ["white", "pink", "green", "yellow-8", "red", "red-4"];
    var ramdom_colors_gen = [];
    var managerSystemServices = [
      {
        label: "Commerce - gestion - stock - vente",
        value: 1,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P001",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module intègre des capacité de gestion d'une entité commerciale en matière de gestion de stock, de vente et bien d'autre fonctionnalités",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Hotel",
        value: 2,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P002",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module intègre des fonctionnalités permettant de gérer un hôtel(Logement, réservations, restaurant interne, boite de nuit, bar et bien de choses",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Bar - resto - night-club",
        value: 3,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P003",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module permet de gérer une entité comme un restaurant, et plusieurs autres entités du même type.",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Transport",
        value: 4,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P004",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module dispose de fonctionnalités permettant de rendre vos service disponible en ligne",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Gestion - personnel",
        value: 5,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P005",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module rassemble l’ensemble des tâches administratives essentielles à une bonne gestion des ressources humaines.",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Schola - management",
        value: 6,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P006",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module intègre des fonctionnalités permettant la gestion d'une institution scolaire.",
        location: {
          lat: 0,
          lng: 0,
        },
      },
      {
        label: "Finances",
        value: 7,
        old_key: "",
        key: "MNGV-ASXR-AMXR-P007",
        key_begin: "",
        key_end: "",
        key_time: 0,
        keygiven: "",
        details:
          "Ce module intègre des fonctionnalités permettant de gérer de vos finances. Il prend en charge vos entrées des autres modules en compte. Il vous permet des gérer vos autres dépenses et entrées par des comptes.",
        location: {
          lat: 0,
          lng: 0,
        },
      },
    ];

    function gen_ramdom_colors() {
      for (let i = 0; i < 7; i++) {
        ramdom_colors_gen.push(ramdom_colors[Math.floor(Math.random() * 6)]);
      }
    }
    gen_ramdom_colors();
    return {
      managerSystemServices,
      ramdom_colors_gen,
    };
  },
});
</script>
