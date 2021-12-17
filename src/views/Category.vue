<template>
  <div>
    <v-row>
      <v-col cols="12" lg="12" xl="8">
        <div>
          <div>
            <div>
              <h2 class="text-h4 font-weight-bold">DEPORTES</h2>

              <h4 class="text-h6">TODO EN UN SOLO LUGAR</h4>
            </div>

            <v-divider class="my-4"></v-divider>

            <v-row>
              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/16/mbappe.jpg?itok=1GjpsqoD&changed=1639680005"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          ¿Mbappé prepara su salida del PSG?: 'Tengo ganas de descubrir y viajar'
                        </div>

                        <div class="text-body-1 py-4">
                          El futuro del futbolista francés podría estar en el Real Madrid; asegura tener buena conexión con Benzema
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">30 Noviembre 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/15/argetina_ok.jpg?itok=kzUWDAHV&changed=1639593715"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Argentina vs Italia: Duelo de campeones continentales será el 1 de junio de 2022 en Londres
                        </div>

                        <div class="text-body-1 py-4">
                          El campeón de la Copa América y el de Eurocopa se enfrentarán tras el acuerdo entre Conmebol y UEFA
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">16 Agosto 2020</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/15/ngb5xvvjuvejhhnnlq7mkgoqd4.jpg?itok=H3_ZbBjD&changed=1639626173"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Checo Pérez: Honda reconoció el gran año que tuvo el mexicano con Red Bull
                        </div>

                        <div class="text-body-1 py-4">
                          UCheco quedó en cuarto lugar en el Campeonato de Pilotos y fue fundamental en la victoria de Verstappen
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">08 Abril 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/15/ap21349718291850_1.jpg?itok=VmxyNW41&changed=1639623727"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          NFL: Anunció que el Super Bowl LVIII se llevará a cabo en Las Vegas
                        </div>

                        <div class="text-body-1 py-4">
                          La nueva y lujosa casa de los Raiders de Las Vegas será la sede del Super Bowl supliendo a New Orleans
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">02 JuLIO 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/16/camilo.jpg?itok=MNr2OXa_&changed=1639675199"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Estrella RÉCORD: Camilo Vargas, el mejor jugador del Apertura 2021
                        </div>

                        <div class="text-body-1 py-4">
                          La comunidad de RÉCORD reconoció la labor del colombiano con el galardón que se entrega cada temporada
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">12 Marzo 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="50"
                  close-delay="50"
                >
                  <div>
                    <v-card
                      flat
                      :color="hover ? 'white' : 'transparent'"
                      :elevation="hover ? 12 : 0"
                      hover
                      to="/detail"
                    >
                      <v-img
                        src="https://www.record.com.mx/sites/default/files/styles/ecrop-horizontal-300x169/public/articulos/2021/12/16/record.jpg?itok=tDCAnkfa&changed=1639662579"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent">VER MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Blue Demon Jr: 'Desde que falleció mi papá nunca volví a poner un árbol de Navidad'
                        </div>

                        <div class="text-body-1 py-4">
                          En entrevista con RÉCORD, el 'Demonio azul' habló de cómo lo marcó la muerte de su padre
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">22 Enero 2020</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>
            </v-row>
          </div>
        </div>
      </v-col>

      <v-col>
        <div>
          <siderbar />
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "Category",
  components: {
    siderbar: () => import("@/components/details/sidebar"),
  },
};
</script>
