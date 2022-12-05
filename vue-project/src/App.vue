<script>
export default {
  name: "App",
};
</script>

<template>
  <div id="app">
    <header>
      <div>
        <img src="./images/Ironhack_logo.png" alt="ironhack-logo" />
      </div>
      <div>
        <img src="./images/Burger_menu.png" alt="burguer-menu"/>
      </div>
    </header>

    <body>
      <div>
        <div class ="pic-body">
        <img src="./images/Vue_logo.png" alt="vue-logo"/>
      </div>
      <h1>Welcome to Vue.js</h1>
      <p>
        Become a coding ninja with the fastest-<br>
        growing JavaScript framework
      </p>
    </div>
    </body>

    <footer>
      <div class ="colum1">
        <img src="./images/USP-1.png" alt="picture-colum1"/>
      
      <h1 title-colum1>Performant</h1>
      <p text-colum1>
        Tryly reactive, compiler-<br>
        optimized renderin<br>
        system that rarely<br>
        requires manual<br>
        optimization.
      </p>
    </div>
      <div colum2>
       
        <img src="./images/USP-2.png" alt="picture-colum2"/>
      
        <h1 title-colum1>Aproachable</h1>
        <p text-colum2>
          Builds on toop of standard<br>
        HTML, CSS and JavaScript<br>
        with intuitive API and<br>
      world-class<br>
      documentation.
        </p>
</div>
        <div colum3>
          <img src="./images/USP-3.png" alt="picture-colum3"/>
        <h1 title-colum3>
          Versatile
        </h1>
        <p text-colum3>
          A rich, incrementally<br>
        adoptable ecosystem<br>
that scales between a<br>
library and a full-<br>
featured framework.
        </p>
        </div>
    </footer>
  </div>
</template>

<style scoped>



header {

  display: flex;
  justify-content: space-between;
  margin-left: 40px;
  margin-right: 40px;
  margin-top: 20px;
}
body {
  display: flex;
justify-content: center;
  background-color: blueviolet;
}
.pic-body {
  display: flex;
justify-content: center;
}

footer {
  display: flex;
justify-content: space-around;
align-items: center;
  background-color: aqua;
}

.colum1 {
display: flex;
justify-content: center;


}

</style>
