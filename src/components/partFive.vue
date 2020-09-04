<template>
  <div class="row  Main justify-content-between">
    <section class="col ">
      <span class="fa fa-youtube" style="color: white; font-size: 30px; padding: 40px"></span>
    </section>

    <section class="col ">
      <span class="fa fa-image" style="color: white; font-size: 30px; padding: 40px"></span>
    </section>

    <section class="col  align-self-center">
      <h1  style="font-weight: bolder; font-family: 'Bebas Neue'; letter-spacing: 10px; font-size: 5rem">GALLERY</h1>
      <p class="text-muted" style="font-size: 15px;">
        commodo vitae, ornare sit amet, wisi. Aenean fermentum,
        elit eget tincidunt condimentum, eros ipsum rutrum orci,
      </p>
      <span>
        <span class="fa fa-close" style="color: #E4003B; font-size: 40px"></span>
        <span style="font-weight: bolder;"> MORE </span>
      </span>
      <h3 style="color: #E4003B;
      opacity: 0.8;
        position: relative;
        transform: rotate(-17deg);
        top: -153px;
        font-weight: bolder;
        font-family: 'Bebas Neue';
        letter-spacing: 10px;
        font-size: 38px;">Foto & Video</h3>

    </section>

  </div>

</template>

<script>
export default {
name: "partFive"
}
</script>

<style scoped>
.Main{
  width: 90%;
  margin: 80px  auto;
  height:50vh;

}
.Main section {
  height: 50vh;
  margin-right: 30px;
  border-radius:10px ;

}
.Main section:first-child {
  background-image: url("../assets/img-section5-gallery.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  box-shadow: 0px 0px 20px gray;

}
.Main section:nth-child(2){
  background-image: url("../assets/img-section5-gallery2.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  box-shadow: 0px 0px 20px gray;

}
.Main section:last-child{
    padding: 100px;
}

</style>
