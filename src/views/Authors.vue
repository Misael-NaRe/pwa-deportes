<template>
  <div>
    <v-row>
      <v-col cols="12" lg="12" xl="8">
        <div>
          <div>
            <div class="my-2">
              <h2 class="text-h4 font-weight-bold">La revolución de los deportes</h2>
            </div>

            <v-row>
              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125222/futbol-mexicano.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          Fútbol
                        </div>

                        <div class="text-body-1 py-4">
                          A la cabeza se encuentra el fútbol, el 58% de las personas prefieren jugarlo o verlo
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125300/taekwondo-mujer-vs-hombre.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          Taekwondo
                        </div>

                        <div class="text-body-1 py-4">
                          En segundo lugar está el taekwondo con más de 2 millones de practicantes
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125332/boxing-mexicana-.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          Box 
                        </div>

                        <div class="text-body-1 py-4">
                          En tercera posición está el box y cuenta con figuras muy conocidas como el Canelo en la división masculina y en la femenina a la Barby.
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125406/beisbol-mexico-1024x647.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                           Béisbol
                        </div>

                        <div class="text-body-1 py-4">
                          Posteriormente, encontramos al béisbol y en México existen dos ligas: La Liga Mexicana de Béisbol y la Liga Mexicana del Pacífico
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125437/futbol-americano-.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          fútbol americano
                        </div>

                        <div class="text-body-1 py-4">
                          El fútbol americano también está dentro de las preferencias y se cuenta con el equipo representativo MondayNightFootball
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125516/lucha-libre.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          lucha libre
                        </div>

                        <div class="text-body-1 py-4">
                          En ascendencia de popularidad está el baloncesto y la lucha libre, gracias a que ahora se pueden hacer apuestas en línea
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://inovafit-com-mx.s3.us-west-2.amazonaws.com/wp-content/uploads/2021/09/09125550/natacion-mexico.jpg.webp"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          Natación
                        </div>

                        <div class="text-body-1 py-4">
                          Por último, pero no menos importante se encuentra la natación, una disciplina prácticamente conquistada por mujeres tan talentosas como Liliana Ibáñez López y Nuria Diosdado
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" >
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
                    >
                      <v-img
                        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrpIV3ZegwAhAR5g58kIcHYIj_KqaqLK0DnQ&usqp=CAU"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="300px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      ></v-img>

                      <v-card-text class="text-center">
                        <v-avatar color="accent" size="86" class="authors">
                          <v-icon dark size="64">mdi-feather</v-icon>
                        </v-avatar>

                        <div
                          class="text-h5 font-weight-bold primary--text pt-4"
                        >
                          Carrera de velocidad
                        </div>

                        <div class="text-body-1 py-4">
                          En el atletismo, la carrera de velocidad es una carrera a pie que tiene una distancia predeterminada en 60, 100, 200 y 400 metros en pistas..
                        </div>

                        <div>
                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>

                          <v-btn icon>
                            <v-icon></v-icon>
                          </v-btn>
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

<style lang="scss" scoped>
.authors {
  position: relative;
  top: -50px;
  margin-bottom: -50px;
}
</style>
