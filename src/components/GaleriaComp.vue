<template>
   <!-- ======= Portfolio Section ======= -->
   <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,700,700i|Montserrat:300,400,500,700" rel="stylesheet">
   <section id="portfolio" class="section-bg">
      <div class="container" data-aos="fade-up">
         <header class="section-header">
            <h3 class="section-title">Galería</h3>
         </header>
         <div class="row" data-aos="fade-up" data-aos-delay="100">
            <div class=" col-lg-12">
            </div>
         </div>
         <div class="row portfolio-container" data-aos="fade-up" data-aos-delay="200">
            <div class="col-lg-4 col-md-6 portfolio-item filter-app">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-web">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/2.png" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-app">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-card">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-web">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-app">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-card">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-card">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-web">
               <div class="portfolio-wrap">
                  <figure>
                     <img src="../assets/4.jpg" class="img-fluid" alt="">
                  </figure>
                  <div class="portfolio-info">
                     <h4><a href="portfolio-details.html">Nombre Proyecto</a></h4>
                     <p>Descripción Proyecto</p>
                  </div>
               </div>
            </div>
         </div>
      </div>
   </section>
   <!-- End Portfolio Section -->
</template>
<script>

</script>
<style scoped>
   body {
   background: #fff;
   color: #666666;
   font-family: "Open Sans", sans-serif;
   }
   a {
   color: #18d26e;
   transition: 0.5s;
   text-decoration: none;
   }
   a:hover,
   a:active,
   a:focus {
   color: #18d36e;
   outline: none;
   text-decoration: none;
   }
   p {
   padding: 0;
   margin: 0 0 30px 0;
   }
   h1,
   h2,
   h3,
   h4,
   h5,
   h6 {
   font-family: "Montserrat", sans-serif;
   font-weight: 600;
   margin: 0 0 20px 0;
   padding: 0;
   }
   #portfolio {
   padding: 60px 0;
   }
   #portfolio #portfolio-flters {
   padding: 0;
   margin: 5px 0 35px 0;
   list-style: none;
   text-align: center;
   }
   #portfolio #portfolio-flters li {
   cursor: pointer;
   margin: 15px 15px 15px 0;
   display: inline-block;
   padding: 10px 20px;
   font-size: 12px;
   line-height: 20px;
   color: #666666;
   border-radius: 4px;
   text-transform: uppercase;
   background: #fff;
   margin-bottom: 5px;
   transition: all 0.3s ease-in-out;
   }
   #portfolio #portfolio-flters li:hover,
   #portfolio #portfolio-flters li.filter-active {
   background: #18d26e;
   color: #fff;
   }
   #portfolio #portfolio-flters li:last-child {
   margin-right: 0;
   }
   #portfolio .portfolio-wrap {
   box-shadow: 0px 2px 12px rgba(0, 0, 0, 0.08);
   transition: 0.3s;
   }
   #portfolio .portfolio-wrap:hover {
   box-shadow: 0px 4px 14px rgba(0, 0, 0, 0.16);
   }
   #portfolio .portfolio-item {
   position: relative;
   height: 360px;
   overflow: hidden;
   }
   #portfolio .portfolio-item figure {
   background: #000;
   overflow: hidden;
   height: 240px;
   position: relative;
   border-radius: 4px 4px 0 0;
   margin: 0;
   }
   #portfolio .portfolio-item figure:hover img {
   opacity: 0.4;
   transition: 0.3s;
   }
   #portfolio .portfolio-item figure .link-preview,
   #portfolio .portfolio-item figure .link-details {
   position: absolute;
   display: inline-flex;
   align-items: center;
   justify-content: center;
   opacity: 0;
   line-height: 1;
   text-align: center;
   width: 36px;
   height: 36px;
   background: #fff;
   border-radius: 50%;
   transition: 0.2s linear;
   }
   #portfolio .portfolio-item figure .link-preview i,
   #portfolio .portfolio-item figure .link-details i {
   font-size: 22px;
   color: #333;
   line-height: 0;
   }
   #portfolio .portfolio-item figure .link-preview:hover,
   #portfolio .portfolio-item figure .link-details:hover {
   background: #18d26e;
   }
   #portfolio .portfolio-item figure .link-preview:hover i,
   #portfolio .portfolio-item figure .link-details:hover i {
   color: #fff;
   }
   #portfolio .portfolio-item figure .link-preview {
   left: calc(50% - 38px);
   top: calc(50% - 18px);
   }
   #portfolio .portfolio-item figure .link-details {
   right: calc(50% - 38px);
   top: calc(50% - 18px);
   }
   #portfolio .portfolio-item figure:hover .link-preview {
   opacity: 1;
   left: calc(50% - 44px);
   }
   #portfolio .portfolio-item figure:hover .link-details {
   opacity: 1;
   right: calc(50% - 44px);
   }
   #portfolio .portfolio-item .portfolio-info {
   background: #fff;
   text-align: center;
   padding: 30px;
   height: 90px;
   border-radius: 0 0 3px 3px;
   }
   #portfolio .portfolio-item .portfolio-info h4 {
   font-size: 18px;
   line-height: 1px;
   font-weight: 700;
   margin-bottom: 18px;
   padding-bottom: 0;
   }
   #portfolio .portfolio-item .portfolio-info h4 a {
   color: #333;
   }
   #portfolio .portfolio-item .portfolio-info h4 a:hover {
   color: #18d26e;
   }
   #portfolio .portfolio-item .portfolio-info p {
   padding: 0;
   margin: 0;
   color: #b8b8b8;
   font-weight: 500;
   font-size: 14px;
   text-transform: uppercase;
   }
</style>
