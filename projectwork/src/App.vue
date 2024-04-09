<template>
  <PortfolioComponent />
  <ResumeComponent />
  <TestimonialComponent />
  <ClientsComponent />
</template>

<script>
import PortfolioComponent from './components/PortfolioComponent.vue'
import ResumeComponent from './components/ResumeComponent.vue'
import TestimonialComponent from './components/TestimonialComponent.vue'
import ClientsComponent from './components/ClientsComponent.vue'

export default {
  name: 'App',
  components: {
    PortfolioComponent,
    ResumeComponent,
    TestimonialComponent,
    ClientsComponent,
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
