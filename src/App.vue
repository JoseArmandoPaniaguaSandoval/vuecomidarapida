<template>
  <div class="azul">
    <div class="container">
      <div class="row text-white">
        <div class="col-md-6 ">Empresa: Mi cocina</div>
        <div class="col-md-6">Paniagua Sandoval Jose Armando 10A DGS</div>
      </div>
    </div>
  </div>
  <br>
  <header>
    <div class="container">
      <div class="row">
        <nav class="menu">

      <ul>
        <li><img src="data:image/png;base64,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" alt="Logo VUE" width="250" height="100"></li>

        <li><a class="text-white btn btn-dark" href="">ENSALADA</a></li>
        <li><a class="text-white btn btn-dark" href="">PLATILLOS</a></li>
        <li><a class="text-white btn btn-dark" href="">BOTELLAS</a></li>
        <li><a class="text-white btn btn-dark" href="">+</a></li>

      </ul>
      </nav>
      </div>
    </div>
    <br>
    <div class="container gris center">
      <h5>¡Eliga con sabidoria!</h5>
    </div>
  </header>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 center azul text-white">Télefono para pedidos: 123 03 09 00   -   Whatsapp: 332 31 31 33</div>
      </div>
    </div>
  </div>

  <div class="container center">
    <h1>Ensalada</h1>
    <card url="https://content-cocina.lecturas.com/medio/2018/07/19/ajoblanco-con-langostinos_aedfeb8f_800x800.jpg" nombre="Sopa de Ajo" descripcion="Incluye un vaso de fruta" costo="100"/>
    <card url="https://cocinarrecetasdepostres.net/wp-content/uploads/2019/11/Ensalada-de-Manzana-Asada-y-Radicchio.jpg" nombre="Ensalada con Manzana y limon" descripcion="Incluye miel y frutos" costo="190"/>
    <card url="https://images.hola.com/imagenes/cocina/recetas/20210528190446/ensalada-rucula-jamon-tomate-parmesano/0-957-715/jamon-salad-adobe-m.jpg" nombre="Ensalada de jamon y queso" descripcion="Incluye tomates y cebolla" costo="200"/>
  
  <card url="https://images.hola.com/imagenes/cocina/noticiaslibros/20210805194067/ensaladas-con-tres-cuatro-ingredientes/0-981-971/ingredientes-adobe-m.jpg" nombre="Ensalada simple" descripcion="Incluye lechuga, tomate y cebolla" costo="101"/>
  <card url="https://embed.widencdn.net/img/mccormick/60ten6ic0l/800x800px/Ensalada%20de%20Vegetales%20y%20Nueces.jpg?crop=true&q=80&color=ffffffff&u=qwwekl" nombre="Ensalada romana" descripcion="Incluye 7 tipo de verduras" costo="290"/>
  <card url="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/salad-with-aragula-tomatoes-orange-beetroot-and-royalty-free-image-1658226846.jpg?crop=0.669xw:1.00xh;0.155xw,0&resize=640:*" nombre="Ensalada de frutas" descripcion="Incluye un jugo gratis" costo="199"/>
  
  </div>

<footer class="text-white">
    <div class="container">
      <h6>Contacto</h6>
      <div class="row">
        
           <ul>
            <li>Correo: Micocina123@gmail.com</li>
            <li>Telefono: 123 03 09 00</li>
            <li>Whatsapp: 332 31 31 33</li>
            <li>AV. lopez col. centro #123</li>
          </ul>
      </div>
    </div>
</footer>
</template>


<script>
  import Card from "./components/Card.vue";
  export default{
    components: { Card},
    
  };
</script>


<style scoped>
footer{
  background-color: black;
}
h1 {
  text-align: center;
}

.center{
  align-content: center;
  text-align: center;
  align-items: center;
}
.der{
  text-align: left;
}
.gris{
  background-color: #E8EAE9;
}
.azul{
  background-color: #06B95D;
}

.menu ul {

  display: flex;
  padding: 0;
  margin: 0;
  list-style: none;

  }

.menu a {
  display: block;
  padding: 0.5em;
  background-color: #06B95D;
  text-decoration: none;
  color: #191C26;

  }

.menu a:hover {

  background-color: #191C26;
  }

.menu ul li ul {
  display: none;
  }

.menu ul li a:hover + ul, .menu ul li ul:hover {
  display: block;
  }

</style>