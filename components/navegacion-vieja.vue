<template lange="html">

<container
>

  <v-navigation-drawer width="300" height="506" floating >
      <v-list-item class="text-h6">
        <v-list-item-content >
          <v-list-item-title class="text-h4" >
            Reseñas
          </v-list-item-title>
          <v-list-item-subtitle class="text-h5">
            Opciones
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider ></v-divider>

      <v-list  dense color="orange" nav >
        <v-list-item
          v-for="item in items"
          :key="item.title"
          link
        >
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

      </v-list>
   </v-navigation-drawer>




</container>

</template>






<script>
  export default {
    data () {
      return {
        items: [
          { title: 'Buscar', icon: 'mdi-account'},
          { title: 'Empresa 1', icon: 'mdi-domain' },
          { title: 'Empresa 2', icon: 'mdi-domain' },
          { title: 'Empresa 3', icon: 'mdi-domain' },
          { title: 'Empresa 4', icon: 'mdi-domain' },
          { title: 'Empresa 5', icon: 'mdi-domain' },
          { title: 'Empresa 6', icon: 'mdi-domain' },
          { title: 'Agregar Reseñista', icon: 'mdi-plus' },
          { title: 'Agregar Empresa', icon: 'mdi-plus' }
        ],
      }
    },
  }
</script>



 <style >

 .text-h4{
  color: white;

 }

 .text-h5{
  color: white;

 }

 .text-h6{
   color: white;
   background: orange;
 }


 </style>

