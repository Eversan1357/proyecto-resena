<template lange="html">


<v-app>

  <v-navigation-drawer>
      <v-list-item >
        <v-list-item-content>
          <v-list-item-title class="text-h6" >
            Reseñas
          </v-list-item-title>
          <v-list-item-subtitle>
            Opciones
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
        dense
        nav
      >
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
        <v-divider></v-divider>
      </v-list>
   </v-navigation-drawer>



</v-app>

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
        right: null,
      }
    },
  }


</script>


<!---
 <style lang="css">

 header{
  margin: 300;

 }

 v-content{
  margin: 50;
 }
 </style>

---->


