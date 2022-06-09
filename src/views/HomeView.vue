<template>
  <div class="home">
    <!-- <h3>Portafolio Alfonso Jose Reyes Valenzuela</h3> -->
 <Navbar />
 <Cv />
 <br><br><br>
 <SobreMi />
 <br><br><br>
 <Cards /><br><br>
 <Carrousel />
 <Footer />
 

    
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Cv     from '@/components/Cv.vue'
import SobreMi from '@/components/SobreMi.vue'
import Cards   from   '@/components/Cards.vue'
import Carrousel from '@/components/Carrousel.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'HomeView',
  components: {
    Navbar,
    Cv,
    SobreMi,
    Footer,
    Carrousel,
    Cards,
    
  }
}
</script>

 Portafolio realizado con informacion tomada de: 
https://www.bootdey.com/snippets/view/candidate-resume#html
https://bbbootstrap.com/snippets/footer-subscribe-our-newsletter-and-social-media-icons-43390415

https://getbootstrap.com/docs/5.1/components/card/
https://www.youtube.com/watch?v=zAVhHHS_IH4&ab_channel=CodingMarket