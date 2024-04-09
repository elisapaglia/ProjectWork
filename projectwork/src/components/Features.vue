<template>
    <div class="rn-section-gap section-separator p-5">
    <div class="  container container-lg container-md container-sm container-xl">
      <span class="textAreaF Fsubtitle">Features</span>
      <h2 class="textAreaF Ftitle">What I Do</h2>
    </div>


    <div class="row">

<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 1</h5>
      <p class="card-text">Descrizione della feature 1.</p>
    </div>
  </div>
</div>


<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 2</h5>
      <p class="card-text">Descrizione della feature 2.</p>
    </div>
  </div>
</div>


<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 3</h5>
      <p class="card-text">Descrizione della feature 3.</p>
    </div>
  </div>  
</div>

<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 4</h5>
      <p class="card-text">Descrizione della feature 4.</p>
    </div>
  </div>  
</div>

<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 5</h5>
      <p class="card-text">Descrizione della feature 5.</p>
    </div>
  </div>  
</div>

<div class="col-12 col-sm-6 col-md-4">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Feature 6</h5>
      <p class="card-text">Descrizione della feature 6.</p>
    </div>
  </div>  
</div>

</div>

    </div> <!--rn-section-gap-->
  </template>
  
  <script>
  export default {
    name: 'Features',
  }
  </script>
  
  <style scoped>

.section-separator {
    position: relative;
    max-width: 1200px;
}
.rn-section-gap {
    padding: 100px 0;
}

.rn-service {
    text-align: left;
    padding: 35px 50px 35px 50px;
    transition: 0.5s all ease-in-out;
    position: relative;
    border-radius: 10px;
    background: var(--background-color-1);
    box-shadow: var(--shadow-1);
    position: relative;
    z-index: 1;
    height: 100%;
}

.rn-service::before {
    content: "";
    position: absolute;
    transition: var(--transition);
    width: 100%;
    height: 100%;
    border-radius: 10px;
    top: 0;
    left: 0;
    background: linear-gradient(to right bottom, #212428, #16181c);
    opacity: 0;
    z-index: -1;
}

*, ::after, ::before {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
  .textAreaF{
    font-family: Montserrat, Popins, sans-serif;
    text-align: left;

  }

  .Ftitle {
        
    margin-top: 15px;
    font-size: 38px;
    line-height: 50px;
    color: white;
    margin-top: 15px;
    margin-bottom: 0;
    font-weight: 700;
    line-height: 1.2;


    margin-bottom: 0;


  }

  .Fsubtitle{
    color: #ff014f;
    text-transform: uppercase;
    font-size: 14px;
    letter-spacing: 1px;
    display: block;
    line-height: 14px;
    margin-bottom: 10px;


  }


 @media (min-width: 1200px)
.container, .container-lg, .container-md, .container-sm, .container-xl {
    max-width: 1140px;
}
@media (min-width: 992px)
.container, .container-lg, .container-md, .container-sm {
    max-width: 960px;
}
@media (min-width: 768px)
.container, .container-md, .container-sm {
    max-width: 720px;
}
@media (min-width: 576px)
.container, .container-sm {
    max-width: 540px;
}
.container, .container-fluid, .container-lg, .container-md, .container-sm, .container-xl, .container-xxl {
    width: 100%;
    padding-right: var(--bs-gutter-x, .75rem);
    padding-left: var(--bs-gutter-x, .75rem);
    margin-right: auto;
    margin-left: auto;
    background-color: rgb(56, 56, 56);
}

@media only screen and (min-width: 992px) and (max-width: 1199px)
.row--25 {
    margin-left: -15px;
    margin-right: -15px;
}

.row--25 {
    margin-left: -25px;
    margin-right: -25px;
}
.row {
    margin-right: -15px;
    margin-left: -15px;
}
.row {
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin-top: calc(var(--bs-gutter-y)* -1);
    margin-right: calc(var(--bs-gutter-x)* -.5);
    margin-left: calc(var(--bs-gutter-x)* -.5);
}

.prova{
    background-color: beige;
}

[data-aos][data-aos][data-aos-duration="500"], body[data-aos-duration="500"] [data-aos] {
    -webkit-transition-duration: .5s;
    -o-transition-duration: .5s;
    transition-duration: .5s;
}

[data-aos][data-aos][data-aos-delay="300"], body[data-aos-delay="300"] [data-aos] {
    -webkit-transition-delay: 0s;
    -o-transition-delay: 0s;
    transition-delay: 0s;
}
  </style>