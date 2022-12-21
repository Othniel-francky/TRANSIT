<template>
  <div class="careau ">
    <nav class="navbar">
        <div class="logo">
            <h1>NVTS</h1>
            <p> <span>N</span>ouvel <span>V</span>ision <span>T</span>ransit <span>S</span>ervice</p>
        </div>
        <div class="nav-link">
            <ul> 
                <li><router-link to="/ACCUEIL">ACCUEIL</router-link></li>
                <li><router-link to="/NVTS LOGISTIC">NVTS LOGISTIC</router-link></li>
                <li><router-link to="/PRESTATION">PRESTATION</router-link></li>
                <li><router-link to="/ENGAGEMENTS">ENGAGEMENTS</router-link></li>
                <li><router-link to="/ESPACE EMPLOI">ESPACE EMPLOI</router-link></li>
                <li><router-link to="/CONTACTS">CONTACTS</router-link></li>
            </ul>

        </div>

    </nav>
</div>
</template>

<script>

</script>
<style scoped>
.logo{
  height: 90px;
  width: 250px;
  border: 1px solid;
  display: flex;
  text-align: center;
  flex-direction: column;
  background-color: black;
}
span{
  font-weight: bold;
  font-size: 25px;
  color: rgb(218, 11, 218);
}

.careau{
  height: 110px;
  width: 100%;
  border-width: 0 4px solid black;
  background-color: violet;
  display: flex;
  align-items: center;
  padding: 0;
  position: absolute;

}

h1{
  font-size: 45px;
  font-weight: bold;
  color: white;
}
.navbar{
  padding: 40px;
  display: flex;
  justify-content: space-between;
  width: 100%;
  box-sizing: border-box;
  align-items: center;
  position: absolute;
}
.navbar .nav-link ul{
  display: flex;
}
.navbar .nav-link ul li{
  margin: 0 25px;
  font-weight: 400;
}
ul li {
  list-style-type: none;

}
li a{
  text-decoration: none;
}
</style>
