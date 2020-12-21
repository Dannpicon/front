<template>
<div class="servicios">
    <div class="serv-card">
    <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img>

    <v-card-title >
      Aplicativo
    </v-card-title>

    <v-card-subtitle>
      Descripción
    </v-card-subtitle>

    <v-card-actions>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show = !show"
      >
        <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          Aplicativo donde el cliente puede registrarse con sus datos y seleccionar el área con la que desea comunicarse, se le asigna un turno, este es enviado vía correo electrónico/mensaje de texto/whatsapp/Facebook. Constantemente se le avisará sobre el tiempo de espera. Para que en dado caso de necesitarlo, pueda cancelar el turno. Cuando llegue el momento de la cita, se le enviará de nuevo una comunicación para que acceda a la línea telefónica. De esta forma el cliente podrá realizar otro tipo de actividades mientras espera su turno, sin preocuparse por esto. Este servicio viene con la capacitación al aplicativo incluida.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
  </div>
  <div class="serv-card">
  <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img>

    <v-card-title>
      Menú Pregrabado
    </v-card-title>

    <v-card-subtitle>
      Descripción
    </v-card-subtitle>

    <v-card-actions>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="shown = !shown"
      >
        <v-icon>{{ shown ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="shown">
        <v-divider></v-divider>

        <v-card-text>
          Cuando el cliente se comunica con su línea de atención, se reproduce un menú donde se le presentan los diferentes servicios que ofrece su empresa y de manera opcional una grabación que describe brevemente los servicios. El cliente selecciona el servicios sobre el cual desea tener mayor información y la llamada se redirige al área correspondiente. De esta manera no existe una única cola de llamadas, lo que disminuye el tiempo de espera del cliente; además, al redirigir la llamada al personal especializado, la llamada se desarrolla de manera más eficiente y exitosa. Este servicio viene con la capacitación al menú pregrabado incluida.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
  </div>
  <div class="serv-card">
  <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img>

    <v-card-title>
      Capacitacion de Personal
    </v-card-title>

    <v-card-subtitle>
      Descripción
    </v-card-subtitle>

    <v-card-actions>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="showed = !showed"
      >
        <v-icon>{{ showed ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="showed">
        <v-divider></v-divider>

        <v-card-text>
          Tener buenos asesores es un factor principal en el éxito de la línea de atención al cliente. Se ofrecen capacitaciones para su personal sobre atención al cliente, trabajo en equipo, trabajo bajo presión, manejo de estrés, manejo de tiempo, habilidades blandas, comunicación efectiva y asertiva y muchas otras más.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
  </div>
</div>
    
</template>
<script>
export default {
    data: () => ({
      show: false,
      shown: false,
      showed: false,
    }),
}
</script>
<style scoped>
    .servicios{
        display: flex;
        
    }
    .serv-card{
        margin-right: 50px;
        margin-left: 50px;
        margin-top: 10px;
        width: 100%;
        height: auto;
    }
</style>