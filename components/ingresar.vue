<template>

<v-container>

    <form  class="form-box animated fadeInUp">
        <h1 class="form-title">Registrese</h1>
        <br>
        <input type="text" placeholder="Username" autofocus>

        <input type="password" placeholder="Password">
        <br>
        <a  type="button" href= pagina-buscar> Ingresar</a>
    </form>

</v-container>

</template>


<style >

.form-box {
    width: 1150px;
    height: 600px;
    padding: 150px;
    background: #191919;
    text-align: center;
}

.form-title {
    color: rgb(252, 156, 46);
    font-weight: 500;
}

.form-box input[type="text"], .form-box input[type="password"], .form-box a[type="button"] {
    border: 0;
    background: none;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 2px solid #3742fa;
    padding: 14px 10px;
    width: 200px;
    outline: none;
    color: white;
    border-radius: 24px;
    transition: 0.25s;
}

.form-box input[type="text"]:focus, .form-box input[type="password"]:focus {
    width: 280px;
    border-color: #ffffff;
}

.form-box a[type="button"] {
    border: 0;
    background: #5352ed;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 2px solid #3742fa;
    padding: 14px 40px;
    outline: none;
    color: white;
    border-radius: 24px;
    transition: 0.25s;
    cursor: pointer;
}

</style>
