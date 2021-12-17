<template>
  <div>
    <div>
      <h3 class="text-h5 font-weight-medium pb-4">LO MEJOR DE LO MEJOR EN DEPORTES</h3>

      <v-divider></v-divider>

      <div>
        <v-row >
          <v-col cols="12" md="6" lg="5">
            <v-card height="100%" flat>
              <v-img
                src="https://cnnespanol.cnn.com/wp-content/uploads/2021/12/211130103921-20211130-golf-climate-change-exlarge-169.jpg?quality=100&strip=info&w=300&h=170&crop=1"
                :aspect-ratio="16 / 9"
                height="100%"
              ></v-img>
            </v-card>
          </v-col>

          <v-col>
            <div>
              <v-btn depressed color="accent" small>VER MAS</v-btn>

              <h3 class="text-h6 font-weight-bold primary--text py-3">
                El golf es un deporte que está destruyendo el planeta. Pero hay solución
              </h3>

              <div class="d-flex align-center">
                <v-avatar color="accent" size="24">
                  <v-icon dark small></v-icon>
                </v-avatar>

                <div class="pl-2">03 MAYO 2020</div>
              </div>
            </div>
          </v-col>
          
        </v-row>
      </div>
    </div>

    <div class="pt-4">
      <h3 class="text-h5 font-weight-medium pb-4">CATEGORIAS</h3>

      <v-divider></v-divider>

      <v-card color="accent" dark flat >
        <v-card-text
          class="d-flex justify-space-between align-center white--text"
        >
          <h6 class="text-h6">FÚTBOL</h6>

          <div class="text-h6">88</div>
        </v-card-text>
      </v-card>

       <v-divider></v-divider>

      <v-card color="accent" dark flat >
        <v-card-text
          class="d-flex justify-space-between align-center white--text"
        >
          <h6 class="text-h6">TENIS</h6>

          <div class="text-h6">45</div>
        </v-card-text>
      </v-card>
       <v-divider></v-divider>

      <v-card color="accent" dark flat >
        <v-card-text
          class="d-flex justify-space-between align-center white--text"
        >
          <h6 class="text-h6">EQUITACIÓN</h6>

          <div class="text-h6">23</div>
        </v-card-text>
      </v-card>
       <v-divider></v-divider>

      <v-card color="accent" dark flat >
        <v-card-text
          class="d-flex justify-space-between align-center white--text"
        >
          <h6 class="text-h6">BOX</h6>

          <div class="text-h6">65</div>
        </v-card-text>
      </v-card>
       <v-divider></v-divider>

      <v-card color="accent" dark flat >
        <v-card-text
          class="d-flex justify-space-between align-center white--text"
        >
          <h6 class="text-h6">GOLF</h6>

          <div class="text-h6">17</div>
        </v-card-text>
      </v-card>
    </div>

    

    <div class="pt-4">
      <h3 class="text-h5 font-weight-medium pb-4">TAGS</h3>

      <v-divider></v-divider>

      <v-row class="pt-2">
        <v-col >
          <v-chip color="accent">#BOX</v-chip>
        </v-col>

        <v-col >
          <v-chip color="accent">#TENIS</v-chip>
        </v-col>

        <v-col >
          <v-chip color="accent">#FUTBOL</v-chip>
        </v-col>
        <v-col >
          <v-chip color="accent">#BEISBOL</v-chip>
        </v-col>
        <v-col >
          <v-chip color="accent">#CARRERA</v-chip>
        </v-col>
        <v-col >
          <v-chip color="accent">#NATACION</v-chip>
        </v-col>
      </v-row>
    </div>
    

    <div class="pt-4">
      <h3 class="text-h5 font-weight-medium pb-4">Registrate</h3>

      <v-divider></v-divider>

      <v-text-field
        label="Correo electronico"
        solo
        type="email"
        outlined
        flat
        class="pt-4"
      ></v-text-field>
      <v-btn color="accent" block large>Subscrbe</v-btn>
    </div>
  </div>
</template>
