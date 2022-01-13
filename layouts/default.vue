<template>
  
  <v-app id="inspire">
    
    <!--Header -->
    
    <v-app-bar color="white" fixed app height="50">
      <FreshMenuLogo/>

      <v-spacer></v-spacer>
      
      <v-btn color=black icon>
      help
    </v-btn>


    <v-btn color=black icon >
      <v-icon >mdi-account</v-icon>
    </v-btn>
    
    </v-app-bar>
    

    <!-- Body -->
     
    <v-main light>
   
      <nuxt /> 
      
      <button/>
     
    </v-main>
    
    <!-- Footer -->
    <Footer/>

  </v-app>
</template>
<style> /* style defines looks of the whole website */
   #inspire {
    background-color: white;
    color: black;
  }
  
</style>