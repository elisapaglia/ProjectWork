<template>
  <div id="portfolio">
    <hr class="mx-3">
    <h6 class="text-center pb-4">VISIT MY PORTFOLIO AND KEEP YOUR FEEDBACK</h6>
    <h2 class="text-center pb-5">My Portfolio</h2>

    <!--- prima riga -->
    <div class="row d-flex">

      <!-- prima card -->
      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-01.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">development</span>
              <div class="d-inline-block float-end">
                <p>600</p>
              </div>
            </div>
            <h5 class="card-title pt-4">The services provide for design</h5>
          </div>
        </div>
      </div>

      <!-- seconda card -->
      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-02.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">application</span>
              <div class="d-inline-block float-end">
                <p>750</p>
              </div>
            </div>
            <h5 class="card-title pt-4">Mobile app landing design & app maintain</h5>
          </div>
        </div>
      </div>


      <!-- terza card -->

      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-03.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">photoshop</span>
              <div class="d-inline-block float-end">
                <p>630</p>
              </div>
            </div>
            <h5 class="card-title pt-4">Logo design creativity & Application</h5>
          </div>
        </div>
      </div>
    </div>


    <!--- seconda riga -->
    <div class="row d-flex pb-5 mb-0">

      <!-- prima card -->
      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-04.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">figma</span>
              <div class="d-inline-block float-end">
                <p>360</p>
              </div>
            </div>
            <h5 class="card-title pt-4">Mobile app landing design & Services</h5>
          </div>
        </div>
      </div>

      <!-- seconda card -->
      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-05.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">web design</span>
              <div class="d-inline-block float-end">
                <p>280</p>
              </div>
            </div>
            <h5 class="card-title pt-4">Design for technology & services</h5>
          </div>
        </div>
      </div>


      <!-- terza card -->

      <div class="col d-flex">
        <div class="card p-4">
          <img src="../assets/portfolio-06.jpg" class="card-img-top" alt="telefonini con app finanziaria">
          <div class="card-body">
            <div>
              <span class="d-inline-block">web design</span>
              <div class="d-inline-block float-end">
                <p>690</p>
              </div>
            </div>
            <h5 class="card-title pt-4">App for technology & services</h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PortfolioComponent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#portfolio {
  background-color: #212529;
  margin-top: 0;
  padding: 0;
}

hr {
  color: black;
  align-items: center;
  margin-top: 0;
}

h6 {
  text-transform: uppercase;
  color: #ff014f;
  padding-top: 80px;
}

h2 {
  font-family: 'Montserrat', sans serif;
  font-size: 60px;
  font-weight: 700;
  color: #c4cfde;
}

.row {
  margin-left: 60px;
  margin-bottom: 60px;
  margin-right: 60px;
  justify-content: center;
}

.card {
  background-color: #212529;
  box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
  width: 100%;
  text-align: left;
  border-radius: 15px;
  box-sizing: border-box;
}

.card-img-top {
  border-radius: 15px;
  height: 100%;
}

span {
  text-transform: uppercase;
  color: #ff014f;
  font-size: 13px;
}

.card p {
  color: #c4cfde;
}

.float-end {
  font-size: 15px;
  font-weight: 700;
  font-family: 'Poppins', sans serif;
}

h5 {
  font-weight: 600;
  font-size: 25px;
  color: #c4cfde;
  line-height: 34px;
  display: inline-block;
}
</style>
