<template>  
  
    <v-footer 
      class="mt-lg-16 mt-md-16 mt-sm-16 mt-16"
      color="grey" 
      > <!-- class above defines the margin between the footer and the caterories' cards-->
        
      <v-container>
        <v-row> <!-- basic steps followed in this footer was to make a container and a row and then make columns as per requirement-->
          <v-col
            cols="12"
            sm="3"
            md="3"
          > <!-- as I required 4 columns, I gave each of them column occupancy of 3 (total columns = 12 so 4x3=12)-->
            <h5>COMPANY</h5>
                
            <v-divider></v-divider>
            <br>
            <font size="2">FAQ<br><br>
              About<br><br>
              Careers<br><br>
              Blog<br><br></font> <!-- '<font>' is used to give all the text within it a defined size -->
          </v-col>
          <v-col
            cols="12"
            sm="3"
            md="3"
            lg="3"
          >
            <h5>HELP & CONTACT</h5>
            <v-divider></v-divider>
            <br>
            <font size="2">Help Center<br><br>
            Email Us<br><br>
            080-6824-5911<br><br></font>
              
          </v-col>
          <v-col
            cols="12"
            sm="3"
            md="3"
          >
            <h5>MORE FROM US</h5>
            <v-divider></v-divider>
            <br> <!-- 'br' provides a break between components (basically spacing)-->
            <font size="2">Bulk/Party Order<br><br>
              Cake Order<br><br>
              FreshClub<br><br>
              Offers<br></br></font>
          </v-col>
                

          <v-col
            cols="12"
            sm="3"
            md="3"
          >
            <h5>CONTACT US</h5>
            <v-divider></v-divider><br>
            <v-row>
              <v-btn icon color="white" class="mt-16 ml-1">
                <v-icon medium>mdi-facebook</v-icon>
              </v-btn> <!-- you add the 'v-btn' tag when you want to make the icon clickable-->
              <v-btn icon color="white"class="mt-16">
                <v-icon medium>mdi-twitter</v-icon>
              </v-btn>
              <v-btn icon color="white" class="mt-16">
                <v-icon medium>mdi-instagram</v-icon> <!-- 'medium' defines the size of the icon-->
              </v-btn>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>

</template>