<template>
  <div class="my-blog">
    <h5>Visit my blog and keep your feedback</h5>
    <h2>My Blog</h2>
    <div class="container mt-5">
  <div class="row">
    <div class="col-md-4">
      <div class="card">
        <img src="https://rainbowit.net/html/inbio/assets/images/blog/blog-01.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <span class="tag">canada</span>
          <span class="time-to-read"><i class="fa-regular fa-clock"></i> 2 min read</span>
          <h3><a href="#">T-shirt design is the part of design <i class="fa-solid fa-square-arrow-up-right"></i></a></h3>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://rainbowit.net/html/inbio/assets/images/blog/blog-02.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <span class="tag2">development</span>
          <span class="time-to-read"><i class="fa-regular fa-clock"></i> 2 hour read</span>
          <h3><a href="#">The services provide for design <i class="fa-solid fa-square-arrow-up-right"></i></a></h3>
        </div>
        <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://rainbowit.net/html/inbio/assets/images/blog/blog-03.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <span class="tag3">application</span>
          <span class="time-to-read"><i class="fa-regular fa-clock"></i>  5 min read</span>
          <h3><a href="#">Mobile app landing design & app maintain <i class="fa-solid fa-square-arrow-up-right"></i></a></h3>
        </div>
      </div>
    </div>
  </div>
</div>
<div class="section"> </div>
    </div>
</template>

<script>
export default {
  name: "MyBlog",
};
</script>

<style scoped>
.my-blog {
  background-color: #212428;
  height: 870px;
}

h5,
h2 {
  letter-spacing: 2px;
  line-height: 1.2;
}

h5 {
  padding-top: 180px;
  font-family: "Poppins", sans-serif;
  font-size: 14px;
  font-weight: 200;
  color: #f9004d;
  text-transform: uppercase;
}

h2 {
  font-family: "Montserrat", sans-serif;
  font-size: 60px;
  font-weight: 700;
  color: #c4cfde;
}

/* Card */

.card {
      margin-bottom: 20px;
      border-radius: 15px;
      overflow: hidden;
      transition: transform 0.5s;
      background-color: #212428;
      box-shadow: rgb(28, 30, 34) 10px 10px 19px 0px, rgb(38, 42, 46) -10px -10px 19px 0px;
      border-radius:20px;
    }
    .card-img-top {
      transition: transform 0.5s;
    }
    .card:hover .card-img-top {
      transform: scale(1.1);
    }
    .card-body {
      padding: 1.5rem;
    }
    .time-to-read {
      color: #c4cfde;
      font-size: 12px;

    }

    .tag {
      color: #f9004d;
      font-size: 0.9rem;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-bottom: 0.5rem;
      margin-right: 210px;
      font-size: 12px;
      }

      h3, h3 a {
        color: #c4cfde;
        font-family: "Montaserrat", sans-serif;
        font-size: 23px;
        font-weight: 550;
        margin-top: 30px;
        margin-left:5px;
        letter-spacing: 1px;
        text-decoration: none;
        text-align: left;
        }
      
      h3 a:hover{
        color: #f9004d;
        text-decoration: none;
      }

      .tag2 {
      color: #f9004d;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-bottom: 0.5rem;
      margin-right: 180px;
      font-size: 12px;
      }

      .tag3 {
      color: #f9004d;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-bottom: 0.5rem;
      margin-right: 180px;
      font-size: 12px;
      }

/* Linea Separatrice */

.section {
    position: relative;
  }

  .section::after {
    content: "";
    position: absolute;
    max-width: 1270px;
    height: 1px;
    background: #121415;
    top: 100%; /* Posiziona subito dopo il contenuto */
    left: 0;
    right: 0;
    margin: 0 auto;
    margin-top: 100px;
  }
</style>
