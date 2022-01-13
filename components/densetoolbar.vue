<template>
  
  <v-toolbar color=white dense lg="12" md="12" sm="12" > <!--defining lg, md, sm makes it responsive (adjusts the size according to screen size) -->

    <FreshMenuLogo/>
     
    <v-spacer></v-spacer> <!-- creates adequate space between logo and icons-->

    <v-btn color=black icon>
      help
    </v-btn>


    <v-btn color=black icon> <!-- color=black defines that the icon or the button should be black in colour-->
      <v-icon>mdi-account</v-icon> 
    </v-btn>

  </v-toolbar>
  
</template>