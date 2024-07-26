<template>
  <footer class="footer-32892 pb-0">
    <div class="site-section">
      <div class="container text-start">
        <div class="row">
          <div class="col-md-3 mb-4 mb-md-0 pb-5">
            <h3>Get in Touch</h3>
            <ul class="list-unstyled quick-info mb-4">
              <li>
                <a href="#" class="d-flex justify-content-start">
                  <span class="icon mr-3 icon-phone"></span> +1 291 3912 329
                </a>
              </li>
              <li>
                <a href="#" class="d-flex justify-content-start">
                  <span class="icon mr-3 icon-envelope"></span> info@gmail.com
                </a>
              </li>
            </ul>
            <ul
              class="list-unstyled social-media mb-4 flex-row d-flex justify-content-start"
            >
              <li>
                <a
                  href="https://facebook.com"
                  target="_blank"
                  class="d-flex align-items-center text-light"
                  ><i class="fa-brands fa-facebook"></i
                ></a>
              </li>
              <li>
                <a
                  href="https://twitter.com"
                  target="_blank"
                  class="d-flex align-items-center px-3 text-light"
                  ><i class="fa-brands fa-x-twitter"></i
                ></a>
              </li>
              <li>
                <a
                  href="https://instagram.com"
                  target="_blank"
                  class="d-flex align-items-center px-1 text-light"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </li>
            </ul>

            <form action="#" class="subscribe">
              <button class="btn text-light border-1 border-light px-5 rounded-0">
                Make a Booking
              </button>
            </form>
          </div>

          <div class="col-md mb-4 mb-md-0">
            <h3>Latest Tweet</h3>
            <ul class="list-unstyled tweets">
              <li class="d-flex">
                <div class="mr-4"><span class="icon icon-twitter"></span></div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Facere unde omnis veniam porro excepturi.
                </div>
              </li>
              <li class="d-flex">
                <div class="mr-4"><span class="icon icon-twitter"></span></div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Facere unde omnis veniam porro excepturi.
                </div>
              </li>
              <li class="d-flex">
                <div class="mr-4"><span class="icon icon-twitter"></span></div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Facere unde omnis veniam porro excepturi.
                </div>
              </li>
            </ul>
          </div>

          <div class="col-md-3 mb-4 mb-md-0">
            <h3>Instagram</h3>
            <div class="row gallery">
              <div class="col-6">
                <a href="#"
                  ><img
                    src="../assets/foam-image.jpg"
                    alt="Image"
                    class="img-fluid rounded shadow"
                /></a>
                <a href="#"
                  ><img
                    src="../assets/decomtamination.webp"
                    alt="Image"
                    class="img-fluid rounded shadow"
                /></a>
              </div>
              <div class="col-6">
                <a href="#"
                  ><img
                    src="../assets/ceramic-image.jpg"
                    alt="Image"
                    class="img-fluid rounded shadow"
                /></a>
                <a href="#"
                  ><img
                    src="../assets/polishing-image.jpg"
                    alt="Image"
                    class="img-fluid rounded shadow"
                /></a>
              </div>
            </div>
          </div>

          <div class="col-12">
            <div class="footer-menu-wrap d-md-flex align-items-center">
              <ul class="list-unstyled footer-menu mr-auto">
                <li><a href="#">Home</a></li>
                <li><a href="#">Story</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Packages</a></li>
                <li><a href="#">Contact</a></li>
              </ul>
              <div class="site-logo-wrap ml-auto">
                <a href="#" class="site-logo"> JKW </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  -webkit-transition: 0.3s all ease;
  -o-transition: 0.3s all ease;
  transition: 0.3s all ease;
}
a,
a:hover {
  text-decoration: none !important;
}

.footer-32892 {
  background-color: #202126;
  padding: 2rem 0;
  color: #888;
  font-size: 16px;
  letter-spacing: 1px;
}

.footer-32892 h3 {
  font-size: 20px;
  color: #fff;
  margin-bottom: 10px;
}

.footer-32892 .row.gallery {
  margin-right: -5px;
  margin-left: -5px;
}
.footer-32892 .row.gallery > [class^="col-"],
.footer-32892 .row.gallery > [class*=" col-"] {
  padding-right: 5px;
  padding-left: 5px;
}
.footer-32892 .gallery a {
  display: block;
  margin-bottom: 20px;
  -webkit-transition: 0.3s all ease;
  -o-transition: 0.3s all ease;
  transition: 0.3s all ease;
}
.footer-32892 .gallery a:hover {
  opacity: 0.5;
}
.footer-32892 .quick-info li {
  color: #fff;
  font-size: 16px;
}
.footer-32892 .quick-info li a {
  color: #fff;
}
.footer-32892 .quick-info li .icon {
  font-size: 20px;
  color: goldenrod;
}
.footer-32892 .subscribe {
  position: relative;
}
.footer-32892 .subscribe .form-control {
  background-color: #292b31;
  -webkit-box-shadow: none;
  box-shadow: none;
  border-radius: 30px;
  height: 55px;
  padding-left: 30px;
  padding-right: 130px;
  border: none;
  color: #fff;
}
.footer-32892 .subscribe .form-control::-webkit-input-placeholder {
  color: #ccc;
  font-size: 14px;
}
.footer-32892 .subscribe .form-control::-moz-placeholder {
  color: #ccc;
  font-size: 14px;
}
.footer-32892 .subscribe .form-control:-ms-input-placeholder {
  color: #ccc;
  font-size: 14px;
}
.footer-32892 .subscribe .form-control:-moz-placeholder {
  color: #ccc;
  font-size: 14px;
}
.footer-32892 .subscribe .btn-submit {
  background: goldenrod;
  letter-spacing: 3px;
  height: 47px;
  border-radius: 30px;
  padding-left: 30px;
  padding-right: 30px;
  color: #fff;
  font-weight: light;
  position: absolute;
  top: 4px;
  right: 4px;
  -webkit-box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.2);
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.2);
}
.footer-32892 .tweets li {
  margin-bottom: 25px;
  font-size: 15px;
  font-style: italic;
}
.footer-32892 .tweets li span {
  color: #fff;
}
.footer-32892 .footer-menu-wrap {
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  padding-top: 2rem !important;
  margin-top: 2rem;
}
.footer-32892 .footer-menu {
  margin-bottom: 0;
}
.footer-32892 .footer-menu li {
  display: inline-block;
}
@media (max-width: 767.98px) {
  .footer-32892 .footer-menu li {
    display: block;
  }
}
.footer-32892 .footer-menu li a {
  padding: 10px;
  display: inline-block;
  color: #fff;
}
@media (max-width: 767.98px) {
  .footer-32892 .footer-menu li a {
    display: block;
    padding-left: 0px;
  }
}
.footer-32892 .footer-menu li:first-child a {
  padding-left: 0;
}
.footer-32892 .site-logo {
  color: #fff;
  font-size: 20px;
}
</style>
