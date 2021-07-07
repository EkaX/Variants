<template>
  <!-- Footer Section Begin -->
  <footer class="footer-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-5">
          <div class="footer-left text-left">
            <div class="footer-logo">
              <a href="#">
                <img src="img/Variants.png" alt />
              </a>
            </div>
            <ul>
              <li>Address: Pakuwon Center, Jl. Embong Malang No.1-5, Kedungdoro, Tegalsari, Surabaya</li>
              <li>Phone: +6231 60003419</li>
              <li>Email: eka.ardilab@gmail.com</li>
            </ul>
            <div class="footer-social">
              <a href="#">
                <i class="fa fa-facebook"></i>
              </a>
              <a href="#">
                <i class="fa fa-instagram"></i>
              </a>
              <a href="#">
                <i class="fa fa-twitter"></i>
              </a>
              <a href="#">
                <i class="fa fa-pinterest"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col-lg-3 offset-lg-1">
          <div class="footer-widget text-left">
            <h5>Information</h5>
            <ul>
              <li>
              <router-link v-bind:to="'/tentang'">Tentang Kami</router-link>
              </li>
              <!-- <li>
                <a href="#">Checkout</a>
              </li> -->
              <li>
              <router-link v-bind:to="'/kontak'">Kontak Kami</router-link>
              </li>
              <!-- <li>
                <a href="#">Serivius</a>
              </li> -->
            </ul>
          </div>
        </div>
        <!-- <div class="col-lg-3">
          <div class="footer-widget text-left">
            <h5>My Account</h5>
            <ul>
              <li>
                <a href="#">My Account</a>
              </li>
              <li>
                <a href="#">Contact</a>
              </li>
              <li>
                <a href="#">Shop</a>
              </li>
            </ul>
          </div>
        </div> -->
      </div>
    </div>
    <div class="copyright-reserved">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="copyright-text">
              Copyright &copy;
              2019 - 2025 All rights reserved | Variants
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- Footer Section End -->
</template>

<script>
export default {
    name: 'FooterArdilab'
}
</script>