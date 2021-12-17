<template>
  <div>
    <v-footer color="primary" dark app absolute>
      <v-container>
        <v-row align="start">
          <v-col cols="12" md="3">
            <h4 class="text-h5 font-weight-bold">
              DEPORTE TOTAL
            </h4>
            <p class="text-body-1">
              Tienes que luchar para alcanzar tus sueños. Tienes que sacrificarte y trabajar duro para ello. (Lionel Messi)

            </p>
          </v-col>

          <v-col cols="12" md="3">
            <v-list flat color="transparent">
              <v-subheader class="text-h6">DEPORTES</v-subheader>
              <v-subheader class="text-h6">TOP</v-subheader>
              <v-subheader class="text-h6">HISTORIA</v-subheader>
              <v-list-item-group color="primary">
                <v-list-item
                  v-for="(item, i) in heroui"
                  :key="i"
                  :href="item.href"
                  dense
                  target="_black"
                >
                  
                </v-list-item>
              </v-list-item-group>
            </v-list>
          </v-col>

          <v-col cols="12" md="3">
            <v-list flat color="transparent">
              <v-subheader class="text-h6">Noticias</v-subheader>
              <v-subheader class="text-h6">FUTBOL</v-subheader>
              <v-subheader class="text-h6">SERVICIOS</v-subheader>
              <v-list-item-group color="primary">
                <v-list-item
                  v-for="(item, i) in shock"
                  :key="i"
                  :href="item.href"
                  dense
                  target="_black"
                >
                  
                </v-list-item>
              </v-list-item-group>
            </v-list>
          </v-col>

          <v-col cols="12" md="3">
            <div>
              <h5 class="text-h6 font-weight-bold">
                SUSCRIBETE
              </h5>
              <p class="text-body-1">
                LO MEJOR EN DEPORTES SOLO AQUI.
              </p>
            </div>

            <v-row>
              <v-col cols="8">
                <v-text-field
                  label="CORREO ELECTRONICO"
                  solo
                  light
                  hide-details
                ></v-text-field>
              </v-col>

              <v-col cols="4">
                <v-btn large block color="secondary">
                  SUSBRIVIRSE
                </v-btn>
              </v-col>
            </v-row>
          </v-col>
        </v-row>

        <div class="text-center mt-6">
          Creada  &copy;
          <a
            class="white--text"
            href="https://heroui.net"
            target="_blank"
            rel="noopener noreferrer"
            >Por</a
          >
           MISAEL NAVA, MARCO BAUTISTA.
        </div>
      </v-container>
    </v-footer>
  </div>
</template>

<script>
export default {
  data: () => ({
    heroui: [
      {
        text: "Github",
        href: "https://github.com/AGDholo",
      },
      {
        text: "Themes",
        href: "https://heroui.net/",
      },
    ],
    shock: [
      {
        text: "Download",
        href: "https://github.com/AGDholo/giraffe",
      },
      {
        text: "Issues",
        href: "https://github.com/AGDholo/giraffe/issues",
      },
      {
        text: "LICENSE",
        href: "https://github.com/AGDholo/giraffe/blob/master/LICENSE",
      },
    ],
  }),
};
</script>
