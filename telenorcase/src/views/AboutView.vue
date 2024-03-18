<template>
  <div class="image-grid">
    <img src="../images/buckethat.jpg" alt="Description of Image 1">
    <img src="../images/lunchbox.png" alt="Description of Image 3">
    <img src="../images/cup.png" alt="Description of Image 4">
    <img src="../images/totebag.jpg" alt="Description of Image 5">
    <img src="../images/phonecover.png" alt="Description of Image 6">
    <img src="../images/snowglobe.png" alt="Description of Image 7">
    <img src="../images/bunny-torstein.png" alt="Description of Image 8">
    <img src="../images/bunny-marius.png" alt="Description of Image 9">
    <img src="../images/cards-kayak.png" alt="Description of Image 10">
    <img src="../images/socks.jpg" alt="Description of Image 11">
    <img src="../images/tshirt.jpg" alt="Description of Image 12">
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

.navbar-img {
  width: 30px; /* adjust as needed */
  height: auto;
}

.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  gap: 10px;
}

.image-grid img {
  width: 100%;
  height: auto;
}
</style>