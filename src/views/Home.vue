<template>
  <div>
    <div>
      <v-card to="detail">
        <v-img
          src="https://vdpfutbolclub.files.wordpress.com/2021/01/deporte-salud-vdp-pirque.jpg"
          gradient="to top, rgba(25,32,72,.7), rgba(25,32,72,.0)"
          :aspect-ratio="16 / 9"
          height="500px"
          dark
        >
          <v-card-text class="fill-height d-flex align-end">
            <v-row class="flex-column">
              <v-col>
                <v-btn color="accent" to="category">DEPORTES</v-btn>
              </v-col>
              <v-col cols="12" md="10" lg="8" xl="7">
                <h2 class="text-h3 py-3" style="line-height: 1.2">
                 Lo último del mundo deportivo solo aqui
                </h2>
              </v-col>
              <v-col class="d-flex align-center">
                <v-avatar class="elevation-4" color="accent">
                  <v-icon large>mdi-feather</v-icon>
                </v-avatar>

                <div class="text-h6 pl-2"> 02 Diciembre 2021</div>
              </v-col>
            </v-row>
          </v-card-text>
        </v-img>
      </v-card>
    </div>

    <v-row>
      <v-col cols="12" lg="12" xl="8">
        <div>
          <div class="pt-16">
            <h2 class="text-h4 font-weight-bold pb-4">MÁS DE LA LIGA MX</h2>

            <v-row>
              <v-col cols="12" md="6" lg="4" >
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
                        src="https://img.vixdata.io/pd/jpg-large/es/sites/default/files/btg/tech.batanga.com/files/Tecnologias-que-se-usan-en-un-partido-de-futbol-y-otros-deportes-1.jpg"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent" to="category">MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Toluca tiene en la mira hasta cuatro refuerzos para la era Ambriz
                        </div>

                        <div class="text-body-1 py-4">
                          Luego de hacerse oficial la llegada de Ignacio Ambriz a la
                           dirección técnica de Toluca
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2"> 02 Diciembre 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4" >
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
                        src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFRgVEhUYGBgYGBgaGRgaGBgYGBgYGBgaGRkYGBgcIS4lHCErIRgYJjgmKy8xNTU1GiQ7QDs0Py40NTEBDAwMEA8QHhISHzQrJCs0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0Mf/AABEIALcBEwMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAEAAIDBQYBBwj/xAA9EAACAQIEAwYDBQYGAwEAAAABAhEAAwQSITEFQVEGEyJhgZEycaEHFFKx0RUjQpLB8BdicoLh8SSiwjP/xAAZAQADAQEBAAAAAAAAAAAAAAAAAQIDBAX/xAAnEQACAgICAgIBBQEBAAAAAAAAAQIRAyESMUFRFGEEBSIycaEjE//aAAwDAQACEQMRAD8A8nYVE4rhemk1VCEaQroWn211pgNZK4tEOlRMKQDiaYK6gk1YJgtJoSbE3RXsabFSvbgxXMtAyOKQak9cWgCXPTGakaktWHf4EZo3yqWj2oAiIpy09rbKfEpX5gj86TCgCOadFcQVJNAERroFOZa4BQBIKjcU+icCtsAvdkgMAEBjMd/E0Hw6aganXamAGGio2qzxGMRtLdhEEazLt5kM2o/vWhsRbUklNvmBA19/+KABlNI06KdFAEQp+WllrrGgBpauTTgKQSkA1RTiaewriigCNlrjLU7VFcNADaVNpUwHkVwU5hXAtIDqGuq0UwVIFoA6zzXCKSrFK5QBLhBrNWP3rlVXZeKItLmNVFiaJGALV3E2wBpQ90FTXGcmmIGeklSMK6gE1BQsu1TtiGMLOVF0CrIX5n8THSSaWHRWdFJgFlBjXcxWh4hwe075rLhV0zAahTGoAnT1qZOioxcuijR2XX4hzU6qR0PpUGJthXYKZWfCTvlOqz5wRWrwnAke0Tacu6troQpWDOXSCZ6GqHj2FFq5lDTKgnSIiVgGTI8O+nPTmRSTG4ySsrTXBTRToqiB1NYUia6BNADAauOznDVxDsjlgAhaVEmRoB8taK7N4TCuSl9XdyGMAlFVRAABBlnMzroPOtFhuBYJZS3cuJcuAhDcIcbxIyBSo6NOs84qJS8GkYN0/BTYPs+gaGzvtsI0+W9Gce7MJaR7lsEKokBomMup09amx3Bwrjxhiohty6lTBBAMq2zf761WIxS/dgWecgQl3BMBSGOaNdliesVmpNM3lBNUkeNZaTA1YWsHdv3XFq2zFnZgpIDQzEj4iJMV3FYB7bFLqMjjdXUqw9Dy866ErRxvTK41xalZaiiKQwnD2wd6IuooGlBSRSLzVJpITQ5VmmMKjz00vUjHk1GakO1MWgDmWu1JFKiwHBaPw2DBGtBNpUqYoinFpdiaY7F4ULQq0U94vpTxw5omnJX0Ja7BTXCKeUI3pjUmhoksoDS1U6U1DFcLzReg8iu3JpqGky1xBSsKHstILT1Saa6xSKOQQQRuDI+Y1Fbq1hLNz947Ze+gKxJIAiYA6yAI86puyfZl8XnuEkW7UZoUs7sdciAc41J8x1023argb93YbD23XKgm2oUMuQfFBnXXXnUyjZeKSXYL2YtC3mzBhyljt5R61L2y+za+7m/hWV5Rc1p2KuGRFXLbMQ06aEjU07sq7Yi4qwclo53Yx4nmESQBzGY/KK9Ca+ZzT/e9PFDyPLLwj5qxOFe27JcRkdTDIwKsPmDUbV9I8a4DY4hayX1hhpbuKBnRoksp5gk6qdCB7eF9q+zN7AXe7vAFWk23X4HUESROxEiV5TzEE01RkZ+alUU1VonD2Sxgf9DmT5UNlRi5OkR2XdXU2zDzCnTc6Rrpzq/w+KfNnuQXgLvEf0XX0rlq1as2y7jwmVXbvbzCJCkyEQc2A0kDxGjuG8LGID3GcW1UhSqWrl0qSsgsqiQphhmJJJBneayltaPSwfjxhayPa9eL6B+Kdr7jZFy93ctyHuQM7RooMjl60zEdpb11O6uOFVwuZkRczAESImOU6RVc6BM2UhgJAJEhlmRKsNRoDB2qG9w820VrpCM/iVAwJCnUM6TmQHkddtqcaa6ObPiniat9lxwS1hrLh75N3VgU7tGXLAIJV5Gac2x061ZdrrNt8OmIwz50XLbeScyOcxACEDuwQNVAiQCJkk5W0XG0OP8AIc3/AK/F9Ks0ZTh7qBz4yhZY8IKMcup3bxHQaANvOg15KjnhilJtJeGzPCa4RRNxABUKJNJma2JdqgbeiktkmBUrYUg6igdFcVNcqyxKLGlApbJpiY9FkUxhBqYCisDhM5k0KIWBRSqyuYIAmu0+LCwfGoJ0oTLUj3KSDWallHEBBq0w+PkZSKr3aaIS2AJpxlxE42SYkVXtRTvpTcPhi5obtgkDzTYq4fhBCzzpJwYlZmKOLBgGHQEwaKvYVRrUTWCu+4qG7eY6TQA53A2pYey1x0t2xmd2VEHVmIAE8tTUWQxXpn2adlMsYzEr4iP3CHQgc7pHInZfIk8xRFA2bHs5wZMDh1soczGWd/xuQAWA5CAAB0FWTQwGsEGQelCY+4ANTB+U/wDdUuH4hhknE3LrBcxE53KBlGRvANBGXXTz3NXZJecN4UuHV+7VBnc3DAYeJgoY6sehgCAPzLZNPP8Av/ioUurEhh4tZzA5hAAYa7bCldu6U0qA7ZvlSdaxXa7iT3nZbyI9u0zBVa2jZRAJYFgTmIyjpr5VdcQ4iyKxRC7CIAiTmOXNBIkCQSJGgNZvHWXdwcYoUPBZUYrIACuvlrDRryB5is8ltaNccoxf7jKdoeFW+8VsOgRHCE6+C2zZpUmJEZQf93kK5h7IA7mwQxcy1xlKEhdTJJIVF1OnSTTu03dYa69vDZjh7mVpbxOtxBDBSSMymQdd+W1U+M4mzqbVhSlsnxGfG8bd43TScg0nrANZ03o7MefDCPOv3ePRDxjGC5dLISUXKiTp4EAUGOWYyxHVjRo4k6KO6LIYhnR2Vm3icp2E7VVHDldd6tuH2UuqczqhB2YGCI5HrMCPMUpppof4klPkm9vZWjE6GROh69OdBFydSd5JPMmdST1rYWeF2QpPfA6HMUViwUq2gLaLMRME68hNVWOvWrXgsoS6tPeuwYwV+EKunTWd5pxjoz/LcrSk7orvuzIFLqVzTlJETB1ifSprq6Iw6QfmNJqK7ineM7FsswOSyZMAaCf6VNbEoV55lI9RH9BVMxxPTT8oi+KnLbik9p03BFTYbxHWqX2Yk2HKqZNNxWKDGBUl+zpRGG4cCk860e9IXRVOateGYRSkmKfgOGqWOb0p+KdUOVdOtEY8dsTdlRibJDGBpTsLiClWmGyswzbUPxsIIAifKs1NcqEwM3idaVCzSp7L0NsJmNT3Vy6UzDvlNPxLSakCAGTR6o0eVCWNGq1OJWNqlxbKUkirvmKsuFuANarcQ2YzXEuMNBVIRp72OBEUG3EWAyjUVUpcI3qTv605EtEd++Sda5aw7sRCkknQDmaSQWE1pLV9FUMACQCImNwRvy3rKUqZcVfZYcE4Lhkup95PeRJZBHd5hqAwIlhzjnHofQ8fjVHjzAgiQQdPQ15dhcWsfvH8KfCxMOQNVGUSTGvPmajxXaRrxCCVRdAs6keccvKiDbdMqSjriXvaDtawR0tyxKkB9IUnSQdzAk/OKoOx/FUXPhrwBS5qmYBlW7EAMCCMrjQ+YHWhMdeDCBzqke0Zq5KtIy/s9EK4VWKXcMyEKisA7d2VR84GQ+Fkz6w39KP4c+HtB8mIdQ7s7eCWLNGZi+Vp2/OqXs9cfEWXJfNcswYaWZ0IPrIyn5irbhOFa+SA6rljXmQemjR7jcVzPJkjKns3UISjZa2+JoQAhckHwu3jkk8zMgf7fyoy8iYlMrCHRtZEFGG4jnPtVTgbAN5UBzgNEiTIHPM3LTzrRuqZyVAzGAz8yBsPr/elXilKSfIjJGKqjK9qez63sOy21zOnjQyMxK6lQB1EiD5V5Yg6bV9C38baw6B3MAeQJb/KBzrwjE4VrdxkIGh0jYqdVYeRBB9a0qiAa48iKmwYBUggyDIiI6c64tgkxFGJayT5gdNKU9xO38CP/ZJfdkdu4FPiUMCIImD8w0SD7+c1U4q7mcwoUDwqo1ygaATzPMnmSTVhdeTVZihDT1rKD3R0/qMFxTXhnVNGcJMuqn8ae2cE0Ap0qfAznUrvmFanlwu0l/RuON2bZTSKyNhoMCiMZxEnw0MjZda1ySTeiYr2S4l2FS4LEtEUNevg1NavgLUp7Ews4ogb1VXrhJkk1Ml0E61HiiOVOWwQ+ziI3oa45Yya4pqYJUUUDa0qnyUqBUd7oq0Gn3BOlWz2kZc3lM1S3T4tKpqgsPt2VAq04XhUZSapr+HdVDH/AKp2ExZUGleylGzmMwn7wqtC3UKHUUbYxfizGhsffDnSj7JOWkz1HeGUxUmFldqWJsk60mPwDW9TR1iyzMAtBIlaXgoQEE1UY8mK6RDj8A6pJ9az4Ug1r+0XEgVyrHSskTzqskUnoSZMzkDeikjLPlVezTRFlyVgVCQ72aH7Om/8wksFVbLliXyDRlgTzliFjox+VbDEW0tOLls3HnNmUs+XLzD6xHqdtqynZThaIhxOKOVCXRQDld4URknkWYDMJHgYaGJ1/BCb9l8OgGcAwW0EHYkxofLzHWspq5I6McUo2yxwF2wtkXLAOVviJMsOqk8oIIgdKis4sOfiA+Rk/OBMetZ3iVp7X7kIiqrSchZszED4pkTAXQVe8D4bdID5EUcs41PnAE/UU4t3SRhLbsB7T8OdmS7bDOIyMg8REkEMo1jbX0qj7ScKZLVm8RJjI+h0BJZN+W+v+ZfKt9xm7ibdrMuItpJAXLbnWCYJYtEwRMV5PxXFXblx1bM75iSGYEg9SwAEfKK0WnYu9DbNst4hAUbsxyoPmx/Leq/iGIyNmzo4YD4CxAA0iSBr1HnUmKt4iFS85UDxIoyhRPhzDLtMEdd+tVGIwxUxSk+S+i8c5YpXF0yyTKwkGPIwPqKDxiiAehqHC3su+3Op8WQV06j2rDjxkj1JZo5sDvtLYEDNW2D7lbeb47hyhRmKG22YkFV/j+ESToM0b61VKBtU9m3rpWx5C0FsuZpO5J/PWn37YC1N9xciRpQTMwMNVuhW7Iia53mkU+48jQUNkNSMnSlvTUkUlaDNLYxyrSdyNKJwySZNNuWszGKaQgfvKVJkpUAIXjsCY6Tp7VJaUkz0oQGjsNe5VSZJPiseWXLEdaCDUQcMWaaKxGChdBQPlQAiTUcwanWy4qFt6b6EuyRXNObEE6VAWpmapKDVtwJpgxDDY1ALp2mkzU4thJp9ItsNhTdWTrQt7AOk1zAYtk0FWL4sup8NTOTCMSjitD2O4M+Lvi2oIQDNcfTwJsIndidAPmdgaqMNhXe4ERSWZgoUblmMAepNe88C4KmDsLbWM8Au0fE5Gp+XIeQFCQ+inxXZewkFLRd9ETM+W2iqNGdlCt8xqSaFTELhnKBg2fQsFCrp8QVR8MnT/aK1OJvBVJYwOZrH8VxFt1VbfiykmfOiSS2Pm6ouOEcEQ5bz5tdQrHQa6Tz960JTLv8A1/pVbwm4z2keSAVGh6daMvEgb+8R/wAVUVokpe02KzqAoGXOJBj8Lakb8ulYi7hf/IZisAuAT1yqFE+gq37YcSREXMWD94hUFQVIEhjmggQG8jWWxPGsquSQwcysH+ITBB9dajK30jbFxVtgPaG6v3m5lMhSEHTwKFI9w1AOA413Gxqww+AtJbW9in+IFltj4m10LEa6+Ub71RrdM9KcWukZST/k/IPfTK1cI00OlFNZL670JlI0NDQkzqj/AK5Gp8MTnX/Us9dxuKgqW2+oO8deXtSA3F+8iIaxuJu5mJojE44ssUIq1pOV6QkiaygipCFFR2VjenXyOVRRaZFfjlUJovIIod4oJYkuEbGicM8SaCL1JmIFOLpie0J31NKo6VKxjBVng7QiaA7o0fhmgUITLW2BUkiqS7fYHSmriXqrIpl66iDtWexI8Zoj709DspJmmCTIXpoFTG2a73VJotMjQa064tSBDSZCeVIbQ3DxzopcUBpUVqzRaWlAoYk2WXZ1AbodhogzfM7KPcz6VqsP2iuW2JDSs6oxlY8vw/MfWsvwwZbZfkW2/wBPP6mocTjJOlYzl+7R144Ljs9Z4bxS1iUJtkEj4kJGZfmOY89qp+0CLbXOwAYkKigjUuQo9yR/YrzvBYx7brcRmUqdGWASOY10IPQiKvMVxlcTibBusUtq6MdAPEDuROg2HkCTWsXcdnPJJS0en4a2EREGyqAPkAKFx+KysE01AMlo/FsI1jL150YW8MgTpIAI10kAHlNZ/iuIJTvGtuj5f4mUgEiNkcgnUiYrR3qiTz/7Q+IZ3t2wPhDOTBE5jkWJ8lPvWORdasu0TE4hwREZQBtplBHvM+tFdnMArd5duqr2kRpUuUJaCRlhSTtH8OrDWdKh7YET4bMuZiSYiSZ22FVjCDFGKjxzqI4ZulAEuEvBRrXMNgGvOQiuygyzJba4VkHKSq6wSI9964uFNGYUXLSG6gzaslxJMMjKsTlIOhEgjUEA8qTetiSB8TgktZrNxW71WVs6Ele6dA0spWVjw6EA+IztBHe1b07tmbQlieRMQBoPOrLGcXtNb7tFZQ2TMFGR/CAHz3Mx72TMZhpPKhcUhJGVSqqqgKVCnbUsBzJJMkk7a6UojAGGtWeGwRYChUwxmTVxhr+UUPsaBMVw5gJmgcNYl4NaE4oFapbls5iRTrYmOxdsJzqtuUdcts29N+6HpTfehIDsiTRmIQRpSXCEcqe9oxBpFLor6VG/dqVFCJ1YDenZ1rXv2EeEIbfen4/7P3QA23zTGhquEg0Y0uKWYVscR9n9wKpV5J3/AOKD4r2JvWkDg5tpEdaXCQWjM94OlPF9f7FXWL7J30VTEliBHSah4p2Yv2EzuJHOOVDjJBoqjfXpTTdFOGDeAwQwdtKY1lhupHpU7GdW6KlW6poaK6BOgp2AQzgU18UK7icE6CWFP4RhO9v2regzugk7AZhJ9podiLfjHDL1hbaOjAFFckAxLgMVJjQiYI8qZwTg74u6LaKVWCzNlMeHkDtJn869bxmIBJ39IP0OopvZ9Q19mg+FDvA+JhyHy50f+e7ZayvjRjT9nlw/xgD/AE7fWgeL9i2w1przPIUqIiJLMFH517OBWX+0Kyz4F8onIyO3+lWGY+kz8hVyS4ukTH+Ss84wHHLtkDu3IH4T4l/lO3pFFft+9i81sW0lEa4ziYAUgaoZnUjSeRrN3LgEnlFbP7PrCJhcRfuDW+6W0U7sqanL6u0/6a54N33o3yqNdbMZ2+wJTF3nLTNzL8DAaIBo0ZT8O0yPrWs7O9kGvYRFDOgIR30USzDPlgbgSNTr7QMT21D/AH/FB9CbhJHLVRH0Ir2/sFdD4G3cCZM+YwYk5WKBjCjcICNNiK3j2c5lB9nZH8Z9qafs6P4z7CvT6U1pS9AeYH7OT+M+woDjXYx8Ph3dXkDKWkfwzE/UV68are0FsthcQoXMTYugL1ORoHvFKUYtVQJtOzwfhWAD+MtGRxMkbQT+cVqOzvZtMely+pZYvOnkYCsCPmHFebHEuRE6HeNJ+dfRH2e8N+74Cwp+J071vnd8YHopUelY4409lykpKkZJvs5PJz7VIPs2HN2+lenRXDW1L0QeZf4bj8bfSkv2bDm7V6bSp0vQHnC/ZsnN2p3+HSfjb3r0am0qXok86P2dJ+Nvenf4c2/xN716Ga5T16KPO/8ADe3+JvelXolKil6AonaVT1p1m6XIB5TUdpdFnqaWE+P1NbAS27pJCnlNQ4l8wCkc/wAqda+P1NTYpAQMu+tAA91QQmlVnaTGp3RR4EqaJxV4oisR8Mz6VTdrcAuJw2e2dQuZSOekxQ+rEw7gvD0a0kqNUX8hUPGeB2jAyjXSiezz/uLZ/wAi/kKssekqpopAzLcW7LWmRMoA2/KsnxDgvd4m0lvdz6aGvS8QZVP7M7AAczVYuFwbYhDfxCC9bJAtLdQFWPJtyT5CPWs58Iq2CT8Ga7ScDuHIi/xNr84qPgfZW7bxFt2gqr9JmQQZB+dbbG2rxe3mwzEZ/Dcs3FuoRsDcVlR006ZgOtWd1Qg8QjKdfKN6TUZ7DooWJDNIiOhMegO1XXZQS11uQyL6+IkexX3qo4jdRMxdgoEkk6Qo1JPlFavguHCWEAESuY+ZfxSZ56j2rNerDyHzXHUEEESDoQdQQdwRSFONUMwWK+zLDu5Zb1xEJJ7sBDHPKrEfD5EE+dFcF7N3UvK99k7u0pW2AdI5QseHmTOpPXethcYKJO1V+JtPciDCdBuR8+VQ4xG5N9nkvbrs3dzYnHu9vK1yQgzZsrEIgBiC0BSR8969kwNgJbRBsiIvsoHKqR8fbd+4CB1BOczorowyiOsgHTmBrvGhU6D5VSdsQ6KUUppVQHJpl8rlbOYXKcxmAFjUzy0p4qp7U2y+FvWlYK1226KTtLqR/X60gPm+1gw7oltpLsiAEQQXIUaT1NfUlhAiKiiFVQoHQAQB9K8N7H9jLxxVtsSAiW3VviBLspDIqxykAknkDXuoqYgdmuUopVQCpUjSoAU1ylSqgFSpTXKAFSpUqAKdcUh8POajRQrTPM1UK/kR6GnK8jUn5Qa4l+f9f6SWqfFM8zTLbjNvzNVpc9T9aWfzI9DT+f8AX+lFtcdHXIfMRVe+FFuyUGohoHl0ocNzmuvfBEM2nmaF+oL0KjnB9LKg8kqzDhkUHpVWt1QNGHuKQxK7ZgPUUL9QXoZb2GQkKnxqhZCQSAfhBPqawvZnspdS9dGKtgeKe8zBg+YkkrzJ+ceu1XuIuQGZWglHQQebFSrehX2JrJ4H7QnDrav2w0uEY5srKS2Uk6axP/NS8qy7ouLaVo1vFe21rAOuHSy7wVLtsEUgGROrNEdB+VWuMxy3l7y02dLltHQ8/FMqRy/h96xXabAi/iRmcJb7sG5cJACqCwOp5wK2vB8NYuWUNtwqFAEA0KW10QBXHhEAHUbknnV4p0/6CS0Q4jD28QLttmBAQh1OmkRrPLQ7VqhA06VV3MNZSZcTEDxAEL0HkdTr1qpbiJ5PPyBPrpVyzxh2QaqadNZL9pN+I/yn9K7+0m/E38rfpWfy8f2KzSYzDrdTIxYAlTKMyNKkEeJSDGmo5iRVWnCb6OO7xTG2Wl0uIrsF5i265Y5fEGqvPFG6t/I1c/bDDm/8j/pQ/wAnE/Yy2xPZ7Du+dkbNBBKu6zmZWJMHeV36EjnVvWT/AGyerfyP+lIcXPVv5G/Sn8rGgNUTSzVlv2q3Vv5G/SurxNupHzU0/l4wNRNUfaAFxkBO0aHqNefy08qEHE22zH+U1BieJ8tSesge+tHyYPVgP4Dw9xeVoy20zNE5ZYqVAygQwOZiSSDKr51rZrJWeJNHhPsKeOKP1PsalflY0gNTNKayzcTfrXBxJzs30o+Xj+wNVNKayq8SfqaceIv1p/Lxis04NKay54i/WkOJv1+lHy8f2M09KazB4o34org4qx0Dij5mP7A080qzP7Qf8VKj5mP7Aru6XoPrT1sD8InrXKVeQAu4HQf3866cOOar7CuUqAHLh16D2FIWB0/KlSoA4bYPIfT9KSoI+ER6fpSpUARz/enp/DVVe7N4ZnNxrK5iZnMRr1gCBSpVUZNdAT3+E23gm2HgzDsYkbGIINGPhAdyfelSocmwEmFA1Bj/AGiam7k7TPotKlSAY1hp/wD0YdQAv6VH92O+d+m+ntXaVADkwnm3uv6V04Yn4WP80f8AzXaVAHAhH8R+h/pT8rfi+g/SlSpAMKN+M+w/SuG0ebt/fypUqYHThh+JvekMItdpUAOFoU4RSpVLAWnl9a5oNhSpUAOPyFNIjlXaVHgBpTXanMvrSpUxkRYTFPFKlUiOz5fU0qVKmB//2Q=="
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent" to="category">MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Furch niega que Atlas sea candidato al título pese a vencer a Pumas
                        </div>

                        <div class="text-body-1 py-4">
                          Julio Furch anotó un golazo en el Olímpico
                           Universitario para darle el triunfo (0-1) al 
                           Atlas sobre Pumas en la ida de las Semifinales
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2"> 02 Diciembre 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>

              <v-col cols="12" md="6" lg="4" >
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
                        src="https://st1.uvnimg.com/dims4/default/ce759a0/2147483647/thumbnail/1240x698/quality/75/?url=http%3A%2F%2Fuvn-brightspot.s3.amazonaws.com%2F3c%2Fa6%2F921400d0499cb2980b77c519307e%2Ffutbol-generic-entry-point.jpg"
                        :aspect-ratio="16 / 9"
                        gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                        height="200px"
                        class="elevation-2"
                        style="border-radius: 16px"
                      >
                        <v-card-text>
                          <v-btn color="accent" to="category">MAS</v-btn>
                        </v-card-text>
                      </v-img>

                      <v-card-text>
                        <div class="text-h5 font-weight-bold primary--text">
                          Diego Cocca no se confía para la Vuelta: "Hemos ganado nada"
                        </div>

                        <div class="text-body-1 py-4">
                         El  entrenador Diego Cocca dejó en claro que Atlas
                          no se confiará este domingo ante Pumas para el juego 
                          de Vuelta a pesar de llegar al Estadio Jalisco
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2"> 02 Diciembre 2021</div>
                        </div>
                      </v-card-text>
                    </v-card>
                  </div>
                </v-hover>
              </v-col>
            </v-row>
          </div>

          <div class="pt-16">
            <h2 class="text-h4 font-weight-bold pb-4">MAS DE BOXEO</h2>

            <v-row>
              <v-col cols="6" lg="4" >
                <v-card flat dark>
                  <v-img
                    src="data:image/jpeg;base64,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"
                    :aspect-ratio="16 / 9"
                    gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                    height="600px"
                    class="elevation-2 fill-height"
                  >
                    <div
                      class="d-flex flex-column justify-space-between fill-height"
                    >
                      <v-card-text>
                        <v-btn color="accent">MAS</v-btn>
                      </v-card-text>

                      <v-card-text>
                        <div
                          class="text-h5 py-3 font-weight-bold"
                          style="line-height: 1.2"
                        >
                          'Pitbull' Cruz: Kambosos me demostró que no hay imposibles
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">03 Diciembre 2021</div>
                        </div>
                      </v-card-text>
                    </div>
                  </v-img>
                </v-card>
              </v-col>

               <v-col cols="6" lg="4" >
                <v-card flat dark>
                  <v-img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlA20PlQY6jn1D2lLHLty6prqYnPzZuEvT4A&usqp=CAU"
                    :aspect-ratio="16 / 9"
                    gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                    height="600px"
                    class="elevation-2 fill-height"
                  >
                    <div
                      class="d-flex flex-column justify-space-between fill-height"
                    >
                      <v-card-text>
                        <v-btn color="accent">MAS</v-btn>
                      </v-card-text>

                      <v-card-text>
                        <div
                          class="text-h5 py-3 font-weight-bold"
                          style="line-height: 1.2"
                        >
                          'Canelo' Álvarez y las batallas en las que ha apoyado fuera del ring
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark></v-icon>
                          </v-avatar>

                          <div class="pl-2">03 Junio 2021</div>
                        </div>
                      </v-card-text>
                    </div>
                  </v-img>
                </v-card>
              </v-col>

               <v-col cols="6" lg="4" >
                <v-card flat dark>
                  <v-img
                    src="data:image/jpeg;base64,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"
                    :aspect-ratio="16 / 9"
                    gradient="to top, rgba(25,32,72,.4), rgba(25,32,72,.0)"
                    height="600px"
                    class="elevation-2 fill-height"
                  >
                    <div
                      class="d-flex flex-column justify-space-between fill-height"
                    >
                      <v-card-text>
                        <v-btn color="accent">MAS</v-btn>
                      </v-card-text>

                      <v-card-text>
                        <div
                          class="text-h5 py-3 font-weight-bold"
                          style="line-height: 1.2"
                        >
                          Fuente: Jessica McCaskill tiene nueva rival para defensa del título
                        </div>

                        <div class="d-flex align-center">
                          <v-avatar color="accent" size="36">
                            <v-icon dark>mdi-feather</v-icon>
                          </v-avatar>

                          <div class="pl-2">03 Mayo 2021</div>
                        </div>
                      </v-card-text>
                    </div>
                  </v-img>
                </v-card>
              </v-col>
            </v-row>
          </div>

          <div class="pt-16">
            <h2 class="text-h4 font-weight-bold">LO MEJOR DE BEISBOL</h2>

            <div>
              <v-row v-for="i in 1" :key="i" class="py-4">
                <v-col cols="12" md="4">
                  <v-card flat height="100%">
                    <v-img
                      src="https://img.mlbstatic.com/mlb-images/image/private/t_16x9/t_w1024/mlb/jkeehyrtuf8hwf3sk65n"
                      :aspect-ratio="16 / 9"
                      height="100%"
                    ></v-img>
                  </v-card>
                </v-col>

                <v-col>
                  <div>
                    <v-btn depressed color="accent">VER MAS</v-btn>

                    <h3 class="text-h4 font-weight-bold pt-3">
                      ‘Big Papi’ es reconocido... ¿previo al Salón?
                    </h3>

                    <p class="text-h6 font-weight-regular pt-3 text--secondary">
                      BOSTON – Los fervientes aficionados del dominicano David Ortiz en Boston tuvieron otra oportunidad de celebrarlo el miércoles por la noche, cuando el “Big Papi” recibió el Premio Baseball Legacy en el Museo del Deporte en New England, como parte del evento anual “La Tradición”. La verdad es que el...
                    </p>

                    <div class="d-flex align-center">
                      <v-avatar color="accent" size="36">
                        <v-icon dark></v-icon>
                      </v-avatar>

                      <div class="pl-2"> 03 Febrero 2020</div>
                    </div>
                  </div>
                </v-col>
              </v-row>
            </div>
          </div>
        </div>
      </v-col>

      <v-col>
        <div class="pt-16">
          <siderbar />
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {
    siderbar: () => import("@/components/details/sidebar"),
  },
};
</script>
