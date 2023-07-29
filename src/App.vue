<script setup>
import NavbarPortofolio from './NavbarPortofolio.vue';
import Jumbotron from './Jumbotron.vue'
import content from './Content.vue'
import content2 from './Content2.vue'
import Kontak from './Kontak.vue';
import project from './Project.vue'
import Footer from './Footer.vue';
</script>
<template>
  <div>
    <div>
    <NavbarPortofolio></NavbarPortofolio>
  </div>
  <div>
  <Jumbotron></Jumbotron>
  </div>
  <br>
  <br>
  <div>
    <content></content>
  </div>
<div>
  <content2></content2>
</div>
<br>
<div>
  <project></project>
</div>
<div>
<Kontak></Kontak>
</div>
<div>
  <Footer></Footer>
</div>
  </div>
</template>

