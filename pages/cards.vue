<template>
  <v-layout>
    <v-flex xs12 sm6 offset-sm3>
       <v-card class="po">
        <v-card-media src="http://www.po.org.ar/uploads/noticias//thumb_ver_nota_zoom/30346.jpg" height="200px">
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">Partido Obrero</h3>
            <div>Sitio web del Partido Obrero de la Argentina</div>
          </div>
        </v-card-title>
        <v-card-actions>
          <v-btn flat class="orange--text" tag="a" href="http://www.po.org.ar" target="_blank">Web</v-btn>
          <v-btn flat class="orange--text" nuxt-link to="/">Home</v-btn>
        </v-card-actions>
      </v-card>
      <v-card class="liverpool">
        <v-card-media src="https://pbs.twimg.com/profile_images/857505840626118656/A1V_u7-u.jpg" height="200px">
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">Liverpool Football Club</h3>
            <div>Sitio web del Liverpool Football Club</div>
          </div>
        </v-card-title>
        <v-card-actions>
          <v-btn flat class="orange--text" tag="a" href="http://www.liverpoolfc.com/welcome-to-liverpool-fc" target="_blank">Web</v-btn>
          <v-btn flat class="orange--text" nuxt-link to="/prueba">Prueba</v-btn>
        </v-card-actions>
      </v-card>
      <v-card class="literautas">
        <v-card-media src="https://1.bp.blogspot.com/-O_EdJex7aUM/V584OJrRUkI/AAAAAAAAAYw/GbpUz-3YDUAOZjCOFERhg4TsY9lN7pv9wCLcB/s1600/literautas.JPG" height="200px">
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">Literautas</h3>
            <div>Sitio web de Literautas</div>
          </div>
        </v-card-title>
        <v-card-actions>
          <v-btn flat class="orange--text" tag="a" href="http://www.literautas.com/" target="_blank">Web</v-btn>
          <v-btn flat class="orange--text" nuxt-link to="/prueba">Prueba</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
    data () {
      return {
        card_text: 'Lorem ipsum dolor sit amet, brute iriure accusata ne mea. Eos suavitate referrentur ad, te duo agam libris qualisque, utroque quaestio accommodare no qui. Et percipit laboramus usu, no invidunt verterem nominati mel. Dolorem ancillae an mei, ut putant invenire splendide mel, ea nec propriae adipisci. Ignota salutandi accusamus in sed, et per malis fuisset, qui id ludus appareat.'
      }
    }
  }
</script>

<style>

h3{
  color:#d3171e;
}

.liverpool{
  display:inline-block;
  margin-right:2%;
  width:49%;
}

.literautas{
  display:inline-block;
  /*margin-right:15px;*/
  /*height:150px;*/
  width:49%;
}

.po{
/*display:inline-block;*/
margin-bottom:15px;
}

</style>