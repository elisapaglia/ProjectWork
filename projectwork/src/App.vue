<template>
  <Navbar />
  <Jumbotron />
  <Features />
  <PortfolioComponent />
  <ResumeComponent />
  <TestimonialComponent />
  <ClientsComponent />
  <MyBlog />
  <ContactMe />
  <frecciaSu />
  <appFooter />
</template>

<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue'
import Features from './components/Features.vue'
import PortfolioComponent from './components/PortfolioComponent.vue'
import ResumeComponent from './components/ResumeComponent.vue'
import TestimonialComponent from './components/TestimonialComponent.vue'
import ClientsComponent from './components/ClientsComponent.vue'
import MyBlog from './components/MyBlog.vue'
import frecciaSu from './components/frecciaSu.vue'
import ContactMe from './components/ContactMe.vue'
import appFooter from './components/appFooter.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    Features,
    PortfolioComponent,
    ResumeComponent,
    TestimonialComponent,
    ClientsComponent,
    MyBlog,
    ContactMe,
    frecciaSu,
    appFooter
  }
}
</script>

<style>
#app {
  font-family: 'Montserrat', 'Poppins', sans serif;
  color: #212529;
  margin: 0;
  padding: 0;
}
</style>
