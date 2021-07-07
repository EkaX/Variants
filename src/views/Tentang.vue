<template>
<div class="Kontak">
	<HeaderArdilab />
		<!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="breadcrumb-text product-more">
              <router-link to="/">
                <i class="fa fa-home"></i> Home
              </router-link>
              <span>Tentang Kami</span>
            </div>
          </div>
        </div>
      </div>
    </div>
		<!-- Breadcrumb Section Begin -->
		<br>
	<section class="h-100 w-100 bg-white" style="box-sizing: border-box;">
		<div class="content-2-1 container-xxl mx-auto p-0  position-relative" style="font-family: 'Poppins', sans-serif">
      <div class="text-center title-text">
        <h2 class="text-title">Tentang Kami</h2>
        <p class="text-caption" style="margin-left: 3rem; margin-right: 3rem">
          You can easily manage your business with a powerful tools
        </p>
      </div>
			<div class="content-3-1 container-xxl mx-auto position-relative" style="font-family: 'Poppins', sans-serif">
			<div class="d-flex flex-lg-row flex-column align-items-center">
				<!-- Left Column -->
        <div class="img-hero text-center justify-content-center d-flex">
          <img id="hero" class="img-fluid"
            src="/img/about.png"
            alt="" />
        </div>
				<!-- Right Column -->
        <div class="container">
          <h2 class="title-text">Lorem Ipsum</h2>
					<br>
          <ul class="p-0 m-0">
            <li class="list-unstyled" style="margin-bottom: 2rem">
              
							<br>
              <p class="text-caption">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. <br>
								Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br>
								when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
              </p>
            </li>
            
          </ul>
          
        </div>
			</div>
			</div>
		</div>

	</section>



	<FooterArdilab />
</div>
</template>

<script>
import HeaderArdilab from "@/components/HeaderArdilab.vue";
import FooterArdilab from "@/components/FooterArdilab.vue";
export default {
    name: "Kontak",
    components: {
        HeaderArdilab,
        FooterArdilab
        
    },
}
</script>