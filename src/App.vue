
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
      <img src="./images/imgCarrito.png" alt="img-carrito" width="50"/>
    </navbar>

    <body>
      <div id="line1">
        <div id="chaquetas">
          <img src="./images/imgChaqueta.png" alt="img-chaqueta" width="80"/>
        </div>
        <p>Seleccione Cantidad</p>
        <a href="boton"> Anadir a Carrito</a>
      </div>

      <div id="line2">
        <div id="pantalones">
          <img src="./images/imgPantalones.png" alt="img-pantalones" width="80"/>
        </div>
        <p>Seleccione Cantidad</p>
        <a href="boton"> Anadir a Carrito</a>
      </div>

      <div id="line3">
        <div id="pantalones">
          <img src="./images/imgCalcetines.png" alt="img-pantalones" width="80"/>
        </div>
        <p>Seleccione Cantidad</p>
        <a href="boton"> Anadir a Carrito</a>
      </div>

    </body>

    <footer>
      <div id="footer">
        <p>
          Formas de pago
        </p>
        
        <div id="imgs-footer">
          <div>
        <img src="./images/imgVisa.png" alt="img-visa" width="30" />
      </div>
       <div>
      <img src="./images/imgMastercard.png" alt="img-Mastercard" width="28" />
    </div>
    <div>
      <img src="./images/imgPaypal.png" alt="img-paypal" width="30"/>
    </div>
    </div>

      </div>
   
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>



<style scoped>

navbar {
  display: flex;
  justify-content: space-between;
align-items: center;
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
  background-color: aqua;
}

#line1 {
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
align-items: center;
}
#line2 {
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
align-items: center;
}

#line3 {
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
align-items: center;
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


#footer {
  margin-top: 30px;
  display: flex;
  justify-content: space-around;
align-items: center;

  background-color: #39b983;
}


#imgs-footer {
  margin-top: 10px;
  margin-bottom: 10px;
  display: flex;

 width: 260px;

display: flex;
justify-content: space-around;
align-items: center;
}


</style>
