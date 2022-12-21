<template>
  <div>
    <div class="image">
      <img src="@/assets/Avion.jpg" alt="">
      <!-- <div class="caro1">
        qsdfghjklertyuiowxcvbn,ertyuidfghj
      </div> -->
    </div>
  </div>
  <div class="tout">
  <div class="container">
    <div class="etape">
      <div class="role">
        <img src="@/assets/blog_3.jpg" alt="">
        <div class="text">
          <h2>FRET ROUTIER</h2>
          <p>Nous disposons d’engin de haute performance capable de contenir jusqu’à 20 tonnes de produits à des frets abordables et accessibles à tous.</p>
        </div>
      </div>

    </div>

    <div class="etape">
      <div class="role">
        <img src="@/assets/blog_4.jpg" alt="">
        <div class="text">
          <h2>LOGISTIQUE</h2>
          <p>Ces années antérieures nous ont permis d’acquérir une bonne maitrise des flux physiques, voire leur bonne gestion afin de procurer une satisfaction effective à notre humble clientèle.</p>
        </div>
      </div>
    </div>

    <div class="etape">
      <div class="role">
        <img src="@/assets/blog_2.jpg" alt="">
        <div class="text">
          <h2>STOCKAGE</h2>
          <p>De grands entrepôts sophistiqués et matériellement équipés capable d’accueillir tout type de produit en fonction de leur nature (conteneur à sec et frigorifié).</p>
        </div>
      </div>
    </div>
  </div>

  <div class="complet">
    <div class="quote-form-area">
      <h3>OBTENEZ UN DEVIS</h3>
      <form action="quote-form">

        <p class="width-full">
          <input type="text" placeholder="Votre nom">
        </p>
        <div class="display">

        <p class="width-half">
          <input type="text" placeholder="Email">
        </p>
        <p>
          <input class="pull-right" type="text" placeholder="Phone">
        </p>

        <p class="width-half">
          <input type="text" placeholder="type">
        </p>
        <p>
          <input class="pull-right" type="text" placeholder="Quantité">
        </p>
      </div>

        <p class="width-full">
          <input type="text" placeholder="Destination">
        </p>

        <p>
          <textarea name="quote-message" id="" cols="43" rows="9"></textarea>
        </p>
        <button type="submit">ENVOYER</button>
      </form>
    </div>

    <div class="autre">
    <h3>NOUS AVONS 17 ANS D'EXPERIENCE DANS CETTE PASSION</h3>
    <p>En constante évolution, CAP LOGISTICS est une entreprise moderne créée depuis 2003 qui est spécialisée dans le domaine du transport routier et de la logistique. Avec un capital de 144 500 000 FCFA, elle est constituée d’une dynamique et compétente équipe qui se fait un devoir d’être à l’écoute des besoins de sa clientèle. Elle a dans sa progression, pris une dimension nationale voire internationale de par ses services au-delà des frontières ivoiriennes notamment dans la sous-région car disposant de fret à destination des pays de l’interland (Burkina-Faso, Mali, Ghana, Togo, Benin, etc.).</p>
  </div>

  </div>

</div>



</template>

<script>
  
</script>

<style scoped>
.complet{
  height: 100%;
  width: 100%;
  border: 1px solid blue;
  padding: 5px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  gap: 5%;
}
.quote-form-area{
  height: 550px;
  width: 400px;
  background: #eef1f5 none repeat scroll 0 0;
  padding: 30px 20px
}
h3{
  color: #3c4a62;
  margin: 0 0 15px;
  font-weight: 700;
  line-height: 1.4em;
  text-transform: uppercase;
  position: relative;
  font-size: 24px;
}
.display{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-content: stretch;
  justify-content: space-between;
}
input{
  padding: 10px;
  margin: 7px;
  border: none;
  height: 48px;
}
button{
  background: #5d6b82 none repeat scroll 0 0;
  border: 0 none;
  border-radius: 5px;
  color: #fff;
  letter-spacing: 2px;
  padding: 10px 20px;
  text-transform: uppercase;
  padding: 5px;
}


img{
  width: 100%;
  height: 100vh;
  
}
.caro1{
  height: 50px;
  width: 150px;
  border: 2px solid red;
  position: absolute;
}
.tout{
  max-width: 1140px;
  margin: 0 auto;
  
}

.container{
  text-align: center;
  display: flex;
  padding: 70px;
}
.etape{
  height: 450px;
  width: 400px;
  border: 1px solid red;
  margin: 10px;
}
.role img {
  max-width: 100%;
  height: auto;

}


</style>
