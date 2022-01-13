<template>
  <v-row>
    <v-col >

      <v-card
        class="pa-4 mt-lg-n16 mt-md-n16 mt-sm-n16 mt-n16 rounded-0" 
        flat
        
        img="foodimage.jpg"
      > <!-- 'm' is for defining margin, 'p' is for padding and rounded-0 makes the component sharp i.e. w/o any round edges-->
          
        <v-row align="center">
          <v-col 
            cols="2" >
            <v-btn href="#categories" height="40" top class="yellow darken-2 mt-lg-n12 ml-lg-n5 mt-md-n12 ml-md-n5 mt-sm-n12 ml-sm-n5 mt-n9 ml-n4 rounded-0 " >CATEGORY</v-btn>
          </v-col> 
          <!-- 'href=#categories' is providing an in-page link. on clicking this particular button, it will redirect the user to the categories' section-->
          <!-- the follow up of this 'href' is in 'index page' where I've defined that section by giving it an id;'categories'-->

          <v-col align="right"
            cols="12" lg="4" md="4" sm="4" offset-lg="6" offset-md="6" offset-sm="6"> 
            <!-- offset defines the space of the component from the left side-->

            

            <v-btn text icon >
             

              <v-icon Normal class="grey-lighten-5 mt-lg-n0   mt-md-n1 ml-md-n4  mt-sm-n1 mb-sm-11 mt-n16 mb-16">mdi-magnify</v-icon>
            </v-btn> 
            <!-- 'normal' defines the size of the icon. everything else in the class deifes it's spacing and margin-->

            <v-icon text small class="grey-lighten-5 mt-lg-n11 ml-lg-n1 mt-md-n11 ml-md-n2 mb-md-0 mt-sm-n11 mb-sm-0 mt-n16 mb-16 text-body1 font-weight-medium">OFFERS</v-icon>
            <!-- 'text' tells that we want the icon to be in a text format. 'small' defines the size of the icon. everything else in the class deifes it's spacing and margin-->

          </v-col>
        </v-row>

          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
            <!-- the code in the row below is for the location-search-bar-->
        <v-row justify="center">
          <v-col cols="8" lg="4" md="4" sm="4" >
            <v-text-field centered="false"
              hide-details 
              label="Filled" 
              placeholder="Location" 
              solo
              color="white"
              light
              rounded 
              dense 
              single-line 
              append-icon="mdi-crosshairs-gps"class="shrink" 
              >
              
            </v-text-field>
          </v-col>
        </v-row>

              

          
        
      </v-card>
    </v-col>
  </v-row>
</template>