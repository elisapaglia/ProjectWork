<template>
  <div class="contact" id="contactMe">
    <h5>Contact</h5>
    <h2>Contact With Me</h2>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img
              src="https://rainbowit.net/html/inbio/assets/images/contact/contact1.png"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <h3 class="card-title mt-2">Nevine Acotanza</h3>
              <h6 class="card-text">
                Chief Operating Officer
                <br />
                <br />
                I am available for freelance work. Connect with me via and call
                in to my account.
                <br />
                <br />
                Phone: <a href="tel:019141043264">+01234567890</a>
                <br />
                Email: <a href="mailto:admin@example.com">admin@example.com</a>
              </h6>
              <br />
              <p>
                Find with me
                <br />
                <br />
                <a href="#" class="btn btn-primary"
                  ><i class="fa-brands fa-facebook"></i
                ></a>
                <a href="#" class="btn btn-primary"
                  ><i class="fa-brands fa-linkedin"></i
                ></a>
                <a href="#" class="btn btn-primary"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card2">
            <div class="card-content">
              <form id="contact-form">
                <div class="form-group">
                  <label for="name" id="name">Your name</label>
                  <input type="text" id="name" name="name" required />
                  <label for="phone" id="phone">Phone number</label>
                  <input type="tel" id="phone" name="phone" />
                </div>
                <div class="form-group">
                  <label for="email">Email</label>
                  <input type="email" id="email" name="email" required />
                </div>
                <div class="form-group">
                  <label for="subject">subject</label>
                  <input type="text" id="subject" name="subject" required />
                </div>
                <div class="form-group">
                  <label for="message">Your message</label>
                  <textarea
                    id="message"
                    name="message"
                    rows="4"
                    required
                  ></textarea>
                </div>
                <button type="submit">
                  Send message <i class="fa-solid fa-arrow-right"></i>
                </button>
              </form>
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
  name: "ContactMe",
};
</script>

<style scoped>
/* Chi sono */

.contact {
  background-color: #212428;
  height: 1150px;
}

h5,
h2 {
  letter-spacing: 2px;
  line-height: 1.2;
}

h5 {
  padding-top: 140px;
  font-family: "Poppins", sans-serif;
  font-size: 14px;
  font-weight: 500;
  color: #f9004d;
  text-transform: uppercase;
  letter-spacing: 2px;
}

h2 {
  font-family: "Montserrat", sans-serif;
  font-size: 60px;
  font-weight: 600;
  color: #c4cfde;
  text-transform: capitalize;
  letter-spacing: 1px;
}

/* Card Chi Sono */

.card {
  background-color: #212428;
  -webkit-box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  -moz-box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  border-radius: 16px;
  height: 691px;
}

.card {
  margin-bottom: 20px;
  border-radius: 15px;
  overflow: hidden;
  transition: transform 0.5s;
  background-color: #212428;
  box-shadow: rgb(28, 30, 34) 10px 10px 19px 0px,
    rgb(38, 42, 46) -10px -10px 19px 0px;
  border-radius: 20px;
}
.card-img-top {
  transition: transform 0.5s;
}
.card:hover .card-img-top {
  transform: scale(1.1);
}

.card h3 {
  font-family: "Montserrat", sans-serif;
  font-size: 29px;
  line-height: 44px;
  text-align: left;
  color: #fff;
  font-weight: 700;
  letter-spacing: 1px;
}

.card h6 {
  font-family: "Poppins", sans-serif;
  font-size: 18px;
  line-height: 27px;
  text-align: left;
  color: #878e99;
  font-weight: 400;
}

.card h6 a {
  color: #c4cfde;
  text-decoration: none;
  position: relative;
  display: inline-block;
  transition: 0.5s;
}

.card h6 a::after {
  position: absolute;
  content: "";
  width: 100%;
  height: 2px;
  bottom: -2px;
  left: 0;
  transition: transform 0.25s ease-out;
  transform: scaleX(0);
  transform-origin: bottom right;
}

.card h6 a:hover {
  color: #f9004d;
  text-decoration: underline #f9004d;
}

.card h6 a:hover::after {
  transform-origin: bottom left;
  transform: scaleX(1);
}

.card p {
  font-family: "Poppins", sans-serif;
  font-size: 14px;
  line-height: 21px;
  text-align: left;
  color: #878e99;
  font-weight: 400;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.card p a {
  color: #ffff;
  background-color: #212428;
  border-color: #212428;
  -webkit-box-shadow: -10px -10px 40px -4px rgba(61, 61, 61, 1);
  -moz-box-shadow: -10px -10px 40px -4px rgba(61, 61, 61, 1);
  box-shadow: -10px -10px 40px -4px rgba(61, 61, 61, 1);
  border-radius: 6px;
  width: 60px;
  height: 60px;
  margin-right: 15px;
}

.card p a i {
  display: flex;
  justify-content: center;
  margin-top: 15px;
}

/* Form */
.card2 {
  width: 100%;
  -webkit-box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  -moz-box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  box-shadow: -12px -10px 35px 0px rgba(66, 66, 66, 1);
  border-radius: 16px;
  height: 691px;
}

label {
  width: 100%;
  margin-top: 25px;
  font-family: "Poppins", sans-serif;
  font-size: 12px;
  line-height: 21px;
  text-align: left;
  color: #878e99;
  font-weight: 400;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding-left: 45px;
  padding-bottom: 10px;
}

input {
  width: 90%;
  height: 40px;
  border-radius: 6px;
  background-color: #191b1e;
  box-shadow: rgba(0, 0, 0, 0.7) 1px 4px 2px -3px inset,
    rgba(255, 255, 255, 0.2) -1px -3px 3px -2px inset;
}

textarea {
  margin-top: 5px;
  width: 90%;
  height: 145px;
  border-radius: 6px;
  background-color: #191b1e;
  box-shadow: rgba(0, 0, 0, 0.7) 1px 4px 2px -3px inset,
    rgba(255, 255, 255, 0.2) -1px -3px 3px -2px inset;
}

button {
  margin-top: 15px;
  box-shadow: rgb(28, 30, 34) 10px 10px 19px 0px,
    rgb(38, 42, 46) -10px -10px 19px 0px;
  border-radius: 6px;
  font-family: "Poppins", sans-serif;
  font-size: 14px;
  text-transform: uppercase;
  background-color: #212428;
  color: #ff014f;
  font-weight: 500;
  letter-spacing: 1px; 
  width: 90%;
  height: 60px;
  cursor: pointer;
  position: relative;
  overflow: hidden;
  transition: top 1s ease-in-out;
}

button:hover {
  transform: translateY(-10%);
  top: 1px;
  background-color: #1e2024;
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
