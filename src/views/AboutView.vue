<template>
  <div class="container-fluid pb-5 mb-5">
    <h1>JKW Premium Detailing: A Journey to Excellence</h1>
    <h3 class="container text-decoration-underline">Our Journey</h3>
    <div class="container-fluid card">
      <p class="card-text text-start">
        Founded in the heart of Cape Town by a passionate car enthusiast, JKW
        Premium Detailing began with a dream of transforming automotive care.
        Growing up, weekends were spent polishing, buffing, and perfecting
        family cars, igniting a love for pristine vehicles. <br /><br />In 2024,
        this passion turned into a profession with the establishment of JKW
        Premium Detailing. The mission: to provide top-tier, meticulous car care
        that leaves every vehicle looking showroom-new. With a commitment to
        using only the best products and techniques, JKW quickly gained a
        reputation for excellence. Each car that rolls into JKW's workshop is
        treated with the utmost care, undergoing a transformation that brings
        out its true potential. <br /><br />From deep cleans and ceramic
        coatings to interior rejuvenation and paint protection, JKW's services
        are designed to enhance and protect every aspect of a vehicle. Today,
        JKW Premium Detailing stands as a beacon of quality in the automotive
        detailing industry, trusted by car lovers and professionals alike. The
        story is one of dedication, expertise, and an unrelenting pursuit of
        perfection—because at JKW, every car deserves the best.
      </p>
      <img
        src="../assets/about-image.jpg"
        alt="about-image"
        width="30%"
        height="30%"
        class="rounded shadow "
      />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
h1,
h3 {
  position: relative;
  padding: 50px 10px 30px;
}
.card {
  display: flex;
  flex-direction: row;
  flex-flow: now wrap;
  justify-content: center;
  border: none;
}
.card-text {
  padding: 20px 50px;
  max-width: 50%;
  display: flex;
}
@media screen and (max-width: 1024px) {
  .card {
    display: flex;
    flex-direction: column;
    flex-flow: nowrap;
  }
}
</style>
