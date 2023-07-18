<template>
  <v-app id="inspire">
    <v-app-bar class="color-cards" app> </v-app-bar>
     
    <v-main class="fondo-contenido d-none d-md-block text-center white--text">
      <h2>Prueba Actualizacion</h2>
      <h2>Prueba Actualizacion</h2>   <h2>Prueba Actualizacion</h2>
      <h2>Prueba Actualizacion</h2>
      <h2>Prueba Actualizacion</h2>   <h2>Prueba Actualizacion</h2>
      <v-container class="centrar">
        <v-row>
          <v-col cols="5">
            <h1>Hola! Mi Nombre es</h1>
            <h2>Alberto Onofre Garduño</h2>
            <p>
              Emplear mis conocimientos de Ingeniero de Sistemas en una labor
              que me invite a seguir desarrollándome, un empleo que me permita
              elevar mis capacidades y que me haga crecer personal y
              profesionalmente en comunión con un ambiente de trabajo. Deseo un
              empleo que me permita desarrollarme y crecer profesionalmente.
            </p>
            <v-card
              elevation="0"
              color="transparent"
              width="500px"
              class="mx-auto mt-3"
            >
              <v-row>
                <v-col
                  ><v-btn
                    target="_blank"
                    href="Anexo5.5_SyE1(Alberto)mayo2023Firmado.pdf"
                    rounded="xl"
                    variant="outlined"
                    color="#54b8f6"
                    >Descargar CV</v-btn
                  >
                </v-col>
                <v-col
                  ><v-btn
                    href="https://api.whatsapp.com/send?phone=7222863109"
                    target="_blank"
                    outlined
                    text
                    color="#54b8f6"
                    rounded
                  >
                    Enviar whatsapp &nbsp;
                    <v-icon size="30">mdi-whatsapp</v-icon>
                  </v-btn></v-col
                >
              </v-row>
              <v-row class="text-center py-16">
                <v-col>
                  <v-icon color="blue">mdi-at</v-icon>
                  <a class="white--text" href="mailto:albertssj4@gmail.com"
                    >albertssj4@gmail.com</a
                  ></v-col
                >
                <v-col>
                  <v-icon color="blue">mdi-cellphone-message</v-icon> <br />
                  <span class="white--text">7222863109</span></v-col
                >
                <v-col>
                  <v-icon color="blue">mdi-map-marker-multiple</v-icon>
                  <span class="white--text"
                    >Ixtlahuaca, Estado de Mexico
                  </span></v-col
                >
              </v-row>
            </v-card>
          </v-col>

          <v-col cols="7">
            <v-card
              style="overflow: visible"
              rounded="xl"
              width="400px"
              class="mx-auto color-cards"
            >
              <v-avatar
                style="border-bottom: 10px solid #54b8f6"
                class="mt-n14"
                size="300"
              >
                <v-img cover :src="require('@/assets/img/AOG Feiz.jpg')"> </v-img>
              </v-avatar>
              <v-divider class="mt-2 white mx-10"></v-divider>
              <div class="mt-2">
                <v-row>
                  <v-col
                    ><h4 style="color: #54b8f6">1 año</h4>
                    <h5 class="white--text">Experiencia</h5>
                  </v-col>
                  <v-col
                    ><h4 style="color: #54b8f6">4</h4>
                    <h5 class="white--text">Proyectos</h5></v-col
                  >
                  <v-col
                    ><h4 style="color: #54b8f6">23</h4>
                    <h5 class="white--text">Años</h5></v-col
                  >
                </v-row>
                <v-row>
                  <v-card-text class="white--text">
                    <h2 class="blue--text">EDUCACION</h2>
                    <h2>Tecnologico de Estudios Superiores Jocotitlan</h2>
                    <h3>Ingenieria en sistemas computacionales</h3>
                    <li style="font-weight: bold">Alumno 8 Semestre</li>
                  </v-card-text>
                </v-row>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-container>

      <v-container>
        <v-row wrap>
          <v-col>
            <v-card class="color-cards white--text" rounded="xl" width="300px">
              <v-icon class="mt-3">mdi-robot-confused</v-icon>
              <h3>Experiencia</h3>
              <v-card-text class="white--text">
                Tengo un año de experiencia trabajando con Vue.js, Node.js y
                dominando el desarrollo web utilizando HTML, CSS y JavaScript
                nativo. Durante este tiempo, he tenido la oportunidad de crear
                aplicaciones web interactivas y escalables, construir interfaces
                de usuario reactivas y eficientes. También he trabajado con
                Node.js para desarrollar servidores y APIs robustas.
              </v-card-text>
            </v-card>
          </v-col>
          <v-col>
            <v-card class="color-cards white--text" rounded="xl" width="300px">
              <v-icon class="mt-3">mdi-robot-happy</v-icon>
              <h3>Pasatiempo</h3>
              <v-card-text class="white--text">
                Ayudar a las personas de todo tipo de forma, en especial con lo
                que se. Me gusta socialisar con las personas de esta manera
                puedo conocerlos, y en caso de que sepan lo mismo que yo,
                podamos trabajar en conjunto.
              </v-card-text>
            </v-card>
          </v-col>
          <v-col>
            <v-card class="color-cards white--text" rounded="xl" width="300px">
              <v-icon class="mt-3">mdi-robot-love</v-icon>
              <h3>Gustos</h3>
              <v-card-text class="white--text">
                La competitividad me impulsa a desafiarme a mí mismo y superar
                mis propios límites. Busco constantemente mejorar mis
                habilidades, conocimientos y rendimiento. Es un impulso interno
                que me motiva a dar lo mejor de mí en cada desafío que enfrento.
                A través de la competencia, encuentro la oportunidad de crecer,
                aprender y establecer metas que me impulsen a seguir adelante.
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>

      <v-container class="centarHabilidades">
        <v-row class="text-center mt-5">
          <v-col>
            <h1 class="blue--text">HABILIDADES</h1>
            <v-row>
              <v-col>
                <h1>Frontend</h1>
                <h2>
                  <v-icon color="green">mdi-circle-multiple-outline</v-icon> Vue
                  Js &nbsp; <v-icon color="green">mdi-vuejs</v-icon>
                </h2>
                <h2>
                  <v-icon color="blue">mdi-circle-multiple-outline</v-icon>
                  Vuetify &nbsp; <v-icon color="blue">mdi-vuetify</v-icon>
                </h2>
                <h2>
                  <v-icon color="purple">mdi-circle-multiple-outline</v-icon>
                  Bootstrap &nbsp; <v-icon color="purple">mdi-bootstrap</v-icon>
                </h2>
                <h2>
                  <v-icon color="orange">mdi-circle-multiple-outline</v-icon>
                  Html &nbsp; <v-icon color="orange">mdi-language-html5</v-icon>
                </h2>
                <h2>
                  <v-icon color="blue">mdi-circle-multiple-outline</v-icon> Css
                  &nbsp; <v-icon color="blue">mdi-language-css3</v-icon>
                </h2>
              </v-col>
              <v-col>
                <h1>Backend</h1>
                <h2>
                  <v-icon color="green">mdi-circle-multiple-outline</v-icon>
                  Node Js &nbsp; <v-icon color="green">mdi-nodejs</v-icon>
                </h2>
                <h2>
                  <v-icon color="blue">mdi-circle-multiple-outline</v-icon>
                  API,servicios web &nbsp; <v-icon color="blue">mdi-web</v-icon>
                </h2>
                <h2>
                  <v-icon color="red">mdi-circle-multiple-outline</v-icon>
                  Git,Github &nbsp; <v-icon color="red">mdi-git</v-icon>
                </h2>
                <h2>
                  <v-icon color="orange">mdi-circle-multiple-outline</v-icon>
                  Mysql, Orcale db &nbsp;
                  <v-icon color="orange">mdi-database</v-icon>
                </h2>
                <h2>
                  <v-icon color="yellow">mdi-circle-multiple-outline</v-icon>
                  Javascript &nbsp;
                  <v-icon color="yellow">mdi-language-javascript</v-icon>
                </h2>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>

      <v-container  class="proyectos">
        <h1 class="blue--text">Proyectos Profesionales</h1>
        <v-window v-model="step">

          <v-window-item :value="1">
        <h2>Punto de venta, Ubicacion de productos &nbsp; &nbsp;&nbsp; <v-btn @click="step++" class="color-buttons"   icon="mdi-chevron-right"></v-btn>  </h2>

            <swiper
            :effect="'coverflow'"
            :grabCursor="true"
            :centeredSlides="true"
            :slidesPerView="'auto'"
            :coverflowEffect="{
              rotate: 50,
              stretch: 0,
              depth: 100,
              modifier: 1,
              slideShadows: true,
            }"
            :pagination="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide
            v-for="index in 9" :key="index"
            >

              <v-img  
              style="border-radius:30px"
            
              height="400"

              cover
         
              :src="require(`@/assets/img1/${index}.png`)" />
                
                
                </swiper-slide>
          
          </swiper>
          </v-window-item>
          <v-window-item :value="2">
            <h2> <v-btn @click="step--" class="color-buttons"   icon="mdi-chevron-left"></v-btn>   &nbsp; &nbsp;&nbsp; E-comerce Tienda de Electronica  </h2>

            <swiper
            :effect="'coverflow'"
            :grabCursor="true"
            :centeredSlides="true"
            :slidesPerView="'auto'"
            :coverflowEffect="{
              rotate: 50,
              stretch: 0,
              depth: 100,
              modifier: 1,
              slideShadows: true,
            }"
            :pagination="true"
            :modules="modules"
            class="mySwiper"
          >
          <swiper-slide
            v-for="index in 10" :key="index"
            >

              <v-img  
              style="border-radius:30px"
            
              height="400"

              cover
         
              :src="require(`@/assets/Tienda/${index}.png`)" />
                
                
                </swiper-slide>
          </swiper>
          </v-window-item>
        </v-window>

      
      </v-container>
    </v-main>


  
    <mobile-view class="d-sm-block d-md-none"></mobile-view>

    <v-footer class="flex-grow-1 color-cards">
      <v-card
        elevation="0"
        tile
        color="transparent"
        class="black white--text py-12 px-5 text-center"
        width="100%"
      >
        <v-row class="text-center">
          <v-col>
            <v-card-text class="white--text">
              <h3>Redes Sociales</h3>
            </v-card-text>
            <v-card-text class="pt-2">
              <v-btn
                v-for="(item, index) in icons"
                :key="index"
                class="mx-1"
                :href="item.link"
                border
                size="x-large"
                variant="text"
                :color="item.color"
                :icon="item.icon"
              >
              </v-btn>
            </v-card-text>
          </v-col>
        </v-row>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/effect-coverflow";
import "swiper/css/pagination";
import mobileView from "../components/MobileView.vue"
// import required modules
import { EffectCoverflow, Pagination } from "swiper/modules";

export default {
  components: {
    mobileView,
    Swiper,
    SwiperSlide,
  },
  data: () => ({
    step:1,
    links: [
      { name: "Inicio", to: "/", icon: "mdi-home" },
      {
        name: "Perfil",
        to: "/Alberto/perfilCard",
        icon: "mdi-smart-card-outline",
      },
    ],
    icons: [
      {
        icon: "mdi-google",
        link: "mailto:osopandassj4@gmail.com",
        color: "red",
      },
      {
        icon: "mdi-instagram",
        link: "https://www.instagram.com/fernando_igs/",
        color: "pink",
      },
      {
        icon: "mdi-whatsapp",
        link: "https://wa.me/7222863109",
        color: "green",
      },
      {
        icon: "mdi-facebook",
        link: "https://www.facebook.com/seiden.stx.1",
        color: "blue",
      },
    ],
  }),
  setup() {
    return {
      modules: [EffectCoverflow, Pagination],
    };
  },
};
</script>

<style scoped>
.fondo-contenido {
  background-image: linear-gradient(
    111.4deg,
    #15162a 6.5%,
    rgba(27, 24, 113, 1) 93.2%
  );
}
.centrar {
  display: flex;
  justify-content: center; /* Centrado horizontal */
  align-items: center; /* Centrado vertical */
  margin-top: 50px;
}
.color-cards {
  background-image: linear-gradient(
    111.4deg,
    #15162a 6.5%,
    rgba(27, 24, 113, 1) 93.2%
  );
}


.color-buttons {
  background-image: linear-gradient(
    111.4deg,
    #2d3061 6.5%,
    rgb(105, 201, 9) 93.2%
  );
}
.swiper {
  width: 100%;
  padding-top: 50px;
  padding-bottom: 50px;
 
 
}

.swiper-slide {
  
  width: 700px;
  height: 400px;
 
}




</style>