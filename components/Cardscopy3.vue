<template>
  
  <v-container fluid>
    <v-row 
      class="mx-auto"> <!--v-for will create a forloop for every single 'card' that will extract info from 'cards' in js script-->
      <v-col
        v-for="card in cards" 
        :key="card.title"
        :cols="12" lg="4" md="4" sm="4" 
       > <!--need to define column occupancy for all screen sizes in order to keep it responsive-->
        <v-card>
          <v-img
            :src="card.src"
            class="white--text "
            gradient="to top left, rgba(100,100,100,.33), rgba(25,32,25,.2)"
            height="180px"
          > <!--src="card.src" will take the image from the js script-->
            <v-card-title  v-text="card.title" class="text-h5 font-weight-medium"></v-card-title>
          </v-img>

            
         </v-card>
       </v-col>
    </v-row>
  </v-container>
  
</template>

<script> //'cards:' below holds the data, which is extracted by the 'card.src' code in html. This way we don't have to add img.src individually in html 
  export default {
    data: () => ({
      cards: [
        { title: 'INDIAN THALI', src: 'indianthali.jpeg' },
        { title: 'CONTINENTAL', src: 'continental.jpeg' },
        { title: 'FIT & FAB', src: 'fit&fab.jpg'},
        { title: 'WOK STATION', src: 'wok.jpeg' },
        { title: 'BIG BIRYANI CO.', src: 'biryani.jpg' },
        { title: 'PIZZAS', src: 'pizza.jpg',  },
        { title: 'SNACKS', src: 'snacks.jpeg' },
        { title: 'BEVERAGE', src: 'beverage.jpg'},
        { title: 'DESSERT', src: 'dessert.jpeg' },
        
      ],
    }),
  }
</script>

