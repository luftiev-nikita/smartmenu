<template>
  <v-sheet
    class="mx-auto"
    elevation="0"
    
    color="white"
  ><!-- elevation-0 means that the component is not raised and it does not have any shadow-->
    <v-slide-group
    
    height="400"
    
    show-arrows
    light
      
    > <!--'height=400'helps in defining the height for the sheet-->
      <!-- 'show arrows' is for the arrows that are on the opposite sides of the carousel-->
      <v-slide-item
       v-for="item in items"
       :key
      
      
        
      > 
      <v-col cols="1" lg="1" md="1" sm="1"> <!--need to define column occupancy for all screen sizes in order to keep it responsive-->
        <v-card
        
          color="white"
          class="ma-2 py-1 "
          height="240"
          max-width="750"
         ><!-- defining max-width restricts the card from expanding beyound that defined pixel size-->
        <!-- 'height=240' helps in defining the height of the card-->
        <!-- ma and py is for margin and padding, margin can be defined as the distance between two cards 
        and padding means the distance between the content of the card from the card's border-->
        
          <v-img
            :src="item.src"
          >
          </v-img>

          
        </v-card>
        </v-col>
      </v-slide-item>
    </v-slide-group>
  </v-sheet>
</template>

<script> //src is used for defining the source of the image here
  export default {
    data () {
      return {
        items: [
          {
            src: 'bestsellerimg.jpeg',
          },
          {
            src: 'bestsellerimg2.jpg',
          },
          {
            src: 'bestsellerimg3.jpg',
          },
          {
            src: 'bestsellerimg4.png',
          },
          {
            src: 'bestsellerimg5.png',
          },
          {
            src: 'bestsellerimg6.png',
          },
        ],
      }
    },
  }
</script>