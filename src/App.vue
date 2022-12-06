<script>
export default {
  name: "App",
};
</script>

<template>
  <div id="Carrito">
    <navbar>
      <!-- prueba -->
      <div>
        <img src="./images/imgKemazon.png" alt="img-logo" width="100"/>
      </div>
      <p>
        Kemazon
      </p>
      <img src="./images/imgCarrito.png" alt="img-carrito" width="80"/>
    </navbar>

    <body>
      <div>
        <div id="chaquetas">
          <img src="./images/imgChaqueta.png" alt="img-chaqueta" width="80"/>
        </div>
        <p>Seleccione Cantidad</p>
        <a href="boton"> Anadir a Carrito</a>
      </div>

      <div>
        <div id="pantalones">
          <img src="./images/imgPantalones.png" alt="img-pantalones" width="80"/>
        </div>
        <p>Seleccione Cantidad</p>
        <a href="boton"> Anadir a Carrito</a>
      </div>

    </body>

    <footer>
      <div>
        <p>
          Formas de pago
        </p>
        <img src="./images/imgVisa.png" alt="img-visa" width="30" />
        <img src="./images/imgMastercard.png" alt="img-Mastercard" width="30" />
        <img src="./images/imgPaypal.png" alt="img-paypal" width="30"/>
        
      </div>
   
    </footer>
  </div>
</template>


<style scoped>
navbar {
  display: flex;
  justify-content: space-between;
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
  background-color: aqua;
}

#chachetas {

display: flex;
justify-content: space-around;
}

a {
  display: block;
  width: 80px;
  font-family: Arial;
  font-weight: 600;
  border-radius: 16px;
  padding: 11px 50px;
  text-decoration: none;
  color: white;
  background-color: #34495e;
}



footer {
  margin-top: 30px;

  display: flex;
  justify-content: space-between;
  background-color: #39b983;
}

</style>
