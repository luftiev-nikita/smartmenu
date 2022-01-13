<template>
  
  <v-main>
    <toolbar/>
    <br>
    <v-row>
      <v-col class="ml-2">
       BEST OFFERS
      </v-col> <!--text-body1 defines the size of the text-->
    </v-row>
    <Cardscarousel/>
    <br>
    <v-divider color="black"></v-divider>
    <br>
     

    <v-row>
      <v-col class="ml-2">
      BEST SELLERS
      </v-col> 
    </v-row>
    <Cardscarousel2/>
    <br>
    <v-divider color="black"></v-divider> 
    <br>
    <br>

    <section id="categories"> <!-- this id is a follow up of 'href=#categories' in the toolbar compoent-->
      <v-row>
        <v-col class="ml-2">
        CATEGORIES
        </v-col> <!--text-body1 defines the size of the text-->
      </v-row>
      <Cardscopy3/> 
    </section>
  </v-main>
  
</template>

