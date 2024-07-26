<template>
  <section id="home-body">
    <div class="company-logo-name">
      <h3 class="sub-home-upper-heading display-6 fw-semibold">
        Free Pick & Drop Service
      </h3>
      <h1 class="main-heading display-1 fw-semibold">JKW Premium Detailing</h1>
      <div class="sub-home-heading">
        <h3 class="sub-home-lower-heading display-6 fw-semibold">
          Trusted Since 2024
        </h3>
      </div>
      <div class="container d-flex justify-content-center">
        <div class="scroll"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>
<style scoped>
#home-body {
  background: url(../assets/perhaps-transformed.png);
  height: 100vh;
  background-size: cover;
  background-repeat: no-repeat;
  border: none;
  outline: none;
}
.company-logo-name {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  color: goldenrod;
  letter-spacing: 5px;
}
h1 {
  color: inherit;
  text-decoration: none;
}
h1 {
  display: block;
  position: relative;
  padding: 0.2em 0;
}

h1::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 0.1em;
  background-color: goldenrod;
  opacity: 0;
  transition: opacity 300ms, transform 300ms;
}

h1:hover::after,
h1:focus::after {
  opacity: 1;
  transform: translate3d(0, 0.01em, 0);
}

.company-logo-name:nth-child(2) a {
  overflow: hidden;
}

.company-logo-name:nth-child(2) a::after {
  opacity: 1;
  transform: translate3d(-100%, 0, 0);
}

.company-logo-name:nth-child(2) a:hover::after,
.company-logo-name:nth-child(2) a:focus::after {
  transform: translate3d(0, 0, 0);
}

.company-logo-name:nth-child(3) a::after {
  opacity: 1;
  transform: scale(0);
  transform-origin: center;
}

.company-logo-name:nth-child(3) a:hover::after,
.company-logo-name:nth-child(3) a:focus::after {
  transform: scale(1);
}
.scroll {
  top: 100px;
  width: 60px;
  height: 60px;
  border: 2px solid goldenrod;
  border-radius: 50%;
  position: relative;
  animation: down 1.5s infinite;
  -webkit-animation: down 1.5s infinite;
  &::before {
    content: "";
    position: absolute;
    top: 15px;
    left: 18px;
    width: 18px;
    height: 18px;
    border-left: 2px solid goldenrod;
    border-bottom: 2px solid goldenrod;
    transform: rotate(-45deg);
  }
}

@keyframes down {
  0% {
    transform: translate(0);
  }
  20% {
    transform: translateY(15px);
  }
  40% {
    transform: translate(0);
  }
}

@-webkit-keyframes down {
  0% {
    transform: translate(0);
  }
  20% {
    transform: translateY(15px);
  }
  40% {
    transform: translate(0);
  }
}
</style>
