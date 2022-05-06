<template> 
        <nav class="bg-red respansive clearfix">
            <div class="row">
                <div class="col-8">
                    <ul >
                    <li><a href="#inicio"> Inicio </a></li>
                    <li><a href="#quem Somos"> Quem Somos </a></li>
                    <li><a href="#unidades"> Unidades </a></li>
                    <li><a href="#contato"> Contato </a></li>
                    <li><a href="produtos.html"> Produtos </a></li>
                    </ul>
                </div>
                <div clas="col-4 direira">
                    <ul class="">
                        <li> <a href="login.html"> Entrar</a></li>
                        <li> <a href="carrinho.html">Carrinho</a></li>
                    </ul>
                </div>
            </div>      
        </nav>
        
</template>

<script>
export default {
  name: "NavbarPage",
};
</script>

<style scoped>
nav{ 
        background-color:#C02836;
        height: 50px;
}

nav ul{
        display: block;
}
    
nav ul li{
        display: inline-block;
        line-height: 30px;
        color: #ffffff;
        font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}

nav ul li a{
        color: #ffffff;
        text-decoration: none;
        padding-left: 25px;
        padding-right: 25px;
        padding-top: 15px;
        padding-bottom: 15px;
        /* padding:15px 25px */
}
</style>