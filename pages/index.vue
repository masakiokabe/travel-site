<template>
  <div>
    <Header />
    <Features />
    <Gallery />
    <Banner/> 
    <Review />
    <Footer/>
  </div>
</template>

<script>
import Header from "../components/Header";
import Features from "../components/Features";
import Gallery from "../components/Gallery";
import Banner from "../components/Banner";
import Review from "../components/Review";
import Footer from "../components/Footer";


export default {
  components:{
    Header,
    Features,
    Gallery,
    Banner,
    Review,
    Footer
  }
}
</script>

<style>
</style>
