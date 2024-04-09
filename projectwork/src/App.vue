<template>
  <PortfolioComponent />
  <ResumeComponent />
  <TestimonialComponent />
  <ClientsComponent />
  <MyBlog />
  <ContactMe />
</template>

<script>
import PortfolioComponent from './components/PortfolioComponent.vue'
import ResumeComponent from './components/ResumeComponent.vue'
import TestimonialComponent from './components/TestimonialComponent.vue'
import ClientsComponent from './components/ClientsComponent.vue'
import MyBlog from './components/MyBlog.vue'
import ContactMe from './components/ContactMe.vue'

export default {
  name: 'App',
  components: {
    PortfolioComponent,
    ResumeComponent,
    TestimonialComponent,
    ClientsComponent,
    MyBlog,
    ContactMe,
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
