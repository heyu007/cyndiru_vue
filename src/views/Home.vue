<template>
  <div class="home">
    <!--nav start-->
    <Nav/>
    <!--nav end-->
    <!--main start-->
    <div class="container-fluid" style="width:100%;position: relative;top:40px">
      <div class="row">
        <!--main left start-->

        <!--left start-->
        <div class="col-lg-3">
          <!--notice message-->
          <Notice/>
          <!--about message-->
          <About/>
          <!--label list-->
          <LabelList/>
        </div>
        <!--left end-->

        <!--content start-->
        <div class="col-lg-6">
          <!--carousel-->
          <Carousel/>

          <!--article-->
          <Article/>
        </div>
        <!--content end-->

        <!--right start-->
        <div class="col-lg-3">
          <!--author-->
          <Author/>

          <!--hot article-->
          <HotArticle/>
        </div>
        <!--right end-->
        <!--main left end-->
      </div>
    </div>
    <!--main end-->
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'
import About from '@/components/About.vue'
import Notice from '@/components/Notice.vue'
import LabelList from '@/components/LabelList.vue'
import Carousel from '@/components/Carousel.vue'
import Article from '@/components/Article.vue'
import Author from '@/components/Author.vue'
import HotArticle from '@/components/HotArticle.vue'

export default {
  name: 'Home',
  components: {
    Nav,
    About,
    Notice,
    LabelList,
    Carousel,
    Article,
    Author,
    HotArticle,
  }
}
</script>
