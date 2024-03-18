<template>
  <div>
    <nav class="navbar">
    </nav>
    <div class="image-grid">
      <img src="../images/hoodie.jpg" alt="Hoodie">
      <img src="../images/tshirt.jpg" alt="Tshirt">
      <img src="../images/buckethat.jpg" alt="Buckethat">
      <img src="../images/lunchbox.png" alt="Lunchbox">
      <img src="../images/cup.png" alt="Cup">
      <img src="../images/totebag.jpg" alt="Totebag">
      <img src="../images/phonecover.png" alt="Phonecover">
      <img src="../images/snowglobe.jpg" alt="Snowglobe">
    </div>
  </div>
</template>

<style>
.image-grid {
  display: flex;
  flex-wrap: wrap;
  align-items: stretch; /* Alle bilder vil ha samme høyde */
}

.image-grid img {
  width: 100%;
  height: auto;
  /* Om du ønsker å sette en fast høyde, kan du gjøre det her, f.eks. height: 200px; */
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
