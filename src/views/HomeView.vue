<template>
  <div>
    <Header/>
    <Home/>
    <About/>
    <facts/>
    <skills/>
    <resume/>
    <portfolio/>
    <services/>
    <testimonial/>
    <contact/> 
    <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>Sulaimon Taofeek</h3>
      <p>Et aut eum quis fuga eos sunt ipsa nihil. Labore corporis magni eligendi fuga maxime saepe commodi placeat.</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>MyResume</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you purchased the pro version. -->
        <!-- Licensing information: [license-url] -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/free-html-bootstrap-template-my-resume/ -->
        Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a>
      </div>
    </div>
  </footer><!-- End Footer --> 
  </div>
</template>
<script>
//import Home from '../components/Home/Home.vue';
//import Hometext from '../components/Hometext.vue';
import Header from '@/components/Header/Header.vue';
import Home from '@/components/Home/Home.vue';
import About from '@/components/About/about.vue';
import facts from '@/components/facts/facts.vue';
import skills from '@/components/skills/skills.vue';
import resume from '@/components/resume/resume.vue';
import portfolio from '@/components/portfolio/portfolio.vue';
import services from '@/components/services/services.vue';
import testimonial from '@/components/testimonial/testimonial.vue';
import contact from '@/components/contact/contact.vue';



export default {
  components:{
    //Home,
    //Hometext
    Header,
    Home,
    About,
    facts,
    skills,
    resume,
    portfolio,
    services,
    testimonial,
    contact,

   
  }
}
</script>
