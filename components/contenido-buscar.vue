<template>

   <div>

    <v-container class="der" >
      <header><h3>*Digite el correo electronico que desea buscar.</h3></header>
      <main><input type="email" /></main>
      <footer><button>BUSCAR</button></footer>
    </v-container>

    <br>
    <v-container class="der2">
        <table border="3">
          <tr>
            <th>Correo</th>
            <td>Nombre</td>
            <td>Apellido</td>
            <td>Genero</td>
            <td>Fecha de Nacimiento</td>
            <td>Tipo de Documento de Identidad</td>
            <td>Numero Documento de Identidad</td>
            <td>Paypal</td>
          </tr>
          <tr>
            <th>1</th>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <th>2</th>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <th>3</th>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>
        </table>
    </v-container>

   </div>
</template>




<script>
</script>



<style>

.der2{
  background: #FF7A00;
  border-radius: 15px;
}

.der{
  background: #FF7A00;
  border-radius: 15px;
}

main{
  height: 100px;
  justify-content: center;
}

input{
  width: 1000px;
  height: 30px;
  margin-top: 20px;
  margin-left: 50px;
  color: black;
  background: white;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  display: flex;
  border-radius: 12px;
}

footer{
  height: 100px;
}

button{
color: white;
height: 40px;
width: 100px;
margin-top: 30px;
margin-left: 550px;
font-family: Verdana, Geneva, Tahoma, sans-serif;
background: #50D024;
}

table{
	background-color: white;
	text-align: left;
	border-collapse: collapse;
	width: 100%;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

th, td{
	padding: 20px;
}


tr:nth-child(even){
	background-color: #ddd;
}

tr:hover td{
	background-color: #f7b656;

	color: white;
}

</style>
