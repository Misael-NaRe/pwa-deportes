<template>
  <div>
    <v-row>
      <v-col cols="12" lg="12" xl="8">
        <div>
          <div>
            <v-card flat color="transparent">
              <v-img
                src="https://www.lifeder.com/wp-content/uploads/2019/11/deporte-filosofia-1024x665.jpg"
                :aspect-ratio="16 / 9"
                gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                style="border-radius: 16px"
              ></v-img>

              <v-card-text>
                <div>
                  <v-btn color="accent">ANIMAL</v-btn>
                </div>

                <div class="text-h4 font-weight-bold primary--text pt-4">
                  <h4>Deporte en México</h4>
                </div>

                <div class="text-body-1 py-4">
                  El deporte en México es muy diverso, y en el transcurso de los años han surgido varias figuras que han destacado a nivel tanto nacional como internacional, en el deporte profesional y en el amateur.
                </div>

                <div class="d-flex align-center justify-space-between">
                  <div class="d-flex align-center">
                    <v-avatar color="accent" size="36">
                      <v-icon dark></v-icon>
                    </v-avatar>

                    <div class="pl-2 text-body-1"></div>
                  </div>

                  <div class="d-flex align-center">
                    <div>
                      <v-chip small color="transparent">
                        <v-icon left></v-icon>
                      </v-chip>

                      <v-chip small color="transparent">
                        <v-icon left></v-icon>
                      </v-chip>
                    </div>
                  </div>
                </div>

                <v-divider class="my-4"></v-divider>

                <div>
                  <p class="text-subtitle-1 primary--text font-weight-medium">
                    Gracias a la disciplina histórica se tiene registros de que en México, durante la época prehispánica las actividades físicas eran parte esencial del funcionamiento social de los diferentes pueblos originarios distribuidos a lo largo del territorio.

Estos deportes se realizaban a manera de competencia y tenían un gran peso sobre la sociedad, pues eran muestra del poder político, militar, religioso y de la fuerza física que los jugadores podían demostrar en el campo de juego.

Uno de los juegos más conocidos es El sagrado juego de la pelota, que al día de hoy varios pueblos originarios al sur de México, se han dado a la tarea de revivir y mostrar como parte del Patrimonio Cultural Intangible de la Humanidad.
                  </p>
                </div>

                <div class="py-4">
                  <v-alert
                    class="font-italic text-h6 text-center"
                    border="left"
                    colored-border
                    color="accent"
                  >
                    El deporte en México parece estancado. Un país con más de 122 millones de habitantes no se ha consolidado como una potencia en los Juegos Olímpicos
                  </v-alert>
                </div>

                <div class="text-h5 primary--text font-weight-bold">
                 ¿Qué le pasa al deporte en México?
                  <p class="text-subtitle-1 primary--text font-weight-medium mt-5">
                    El enfrentamiento entre las autoridades deportivas, la falta de recursos económicos y la burocracia impiden a los atletas mexicanos dar el salto a la elite mundial
                  </p>
                </div>

                <div class="my-4">
                  <v-row>
                    <v-col cols="6">
                      <v-card>
                        <v-img
                          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5EN9mZQHmOd4CrcWfkHnAPfC_h8Ym8ufPHw&usqp=CAU"
                          :aspect-ratio="16 / 9"
                          gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        ></v-img>
                      </v-card>
                    </v-col>

                    <v-col cols="6">
                      <v-card>
                        <v-img
                          src="data:image/jpeg;base64,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"
                          :aspect-ratio="16 / 9"
                          gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        ></v-img>
                      </v-card>
                    </v-col>
                  </v-row>
                </div>

                <div class="text-h5 primary--text font-weight-bold">
                  ¿ QUE PREFIEREN LOS MEXICANOS ?
                  <div class="text-subtitle-1 primary--text font-weight-medium mt-5">
                    <ul>
                      <li class="my-2">
                        Futbol: El 58 por ciento de los mexicanos dijo que prefería jugar, ver o consumir este deporte.
                      </li>

                      <li class="my-2">
                        Box: El 34.6 por ciento de la preferencia registrada por los mexicanos, influidos sobre todo por figuras como Saúl “Canelo” Álvarez o Julio César Chávez.
                      </li>

                      <li class="my-2">
                        Basquetball: El 23.8 por ciento de los votos, aunque sí hay escuadras en México, lo cierto es que se concentran en ver la NBA.
                      </li>

                      <li class="my-2">
                        Beisbol: Un 25.2 por ciento, se coloca como la tercera opción más amada por los mexicanos, ya que la Liga en México es bastante buena y tradicional, pero también como referencia de la de Estados Unidos.
                      </li>
                    </ul>

                    
                  </div>
                </div>

                <div class="d-flex align-center justify-space-between mt-8">
                  <div>
                    <v-row>
                      <v-col class="flex-shrink-0" cols="auto">
                        <v-chip color="accent">#Lucha libre</v-chip>
                      </v-col>

                      <v-col class="flex-shrink-0" cols="auto">
                        <v-chip color="accent">#útbol americano</v-chip>
                      </v-col>

                      <v-col class="flex-shrink-0" cols="auto">
                        <v-chip color="accent">#Natación</v-chip>
                      </v-col>
                    </v-row>
                  </div>

                  <div class="text-h5">
                    
                    <v-btn icon large>
                      <v-icon large color="primary"></v-icon>
                    </v-btn>

                    <v-btn icon large>
                      <v-icon large color="primary"></v-icon>
                    </v-btn>

                    <v-btn icon large>
                      <v-icon large color="primary"></v-icon>
                    </v-btn>

                    <v-btn icon large>
                      <v-icon large color="primary"></v-icon>
                    </v-btn>
                  </div>
                </div>

                <v-divider class="my-8"></v-divider>

                <div class="my-8">
                  <div class="d-flex align-center">
                    <v-avatar color="accent" size="128">
                      <v-icon dark size="100"></v-icon>
                    </v-avatar>

                    <div class="pl-4">
                      <div class="text-h5 primary--text font-weight-bold">
                        ¿SABIAS
                        <span class="accent--text">QUE ?</span>
                      </div>

                      <div class="text-subtitle-1 my-2">
                        En los primeros juegos del fútbol mexicano la alineación se componía de: 2 defensas, 3 medios y 5 delanteros (2-3-5) 
                      </div>

                      <div class="text-subtitle-1">
                        
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
                    </div>
                  </div>
                </div>

                <div>
                  <v-row justify="space-between">
                    <v-col cols="12" md="6" lg="4">
                      <div class="d-flex align-center">
                        <div>
                          <v-icon></v-icon>
                        </div>

                        <div class="text-h6 primary--text pl-2">
                          <div class="text-subtitle-1"></div>
                        </div>
                      </div>
                    </v-col>

                    <v-col cols="12" md="6" lg="4">
                      <div class="d-flex align-center text-right">
                        <div class="text-h6 primary--text pr-2">
                          <div class="text-subtitle-1"></div>
                        </div>

                        <div>
                          <v-icon></v-icon>
                        </div>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-card-text>
            </v-card>
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
    siderbar: () => import("@/components/details/sidebar")
  }
};
</script>
