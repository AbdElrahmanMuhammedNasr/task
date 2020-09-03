<template>
    <div class="row Main " >
      <section class="Title col-sm-2  align-self-center"  >
        <h1>ADVICE</h1>
      </section>
      <section class="Image col-sm-10" style="overflow: hidden" >
          <div  style="background-color: #d8efef; width: 25vw; padding: 30px; margin: 34vh -15px">
              <h1  style="font-weight: bolder; font-family: 'Bebas Neue'; letter-spacing: 10px">SURVIVAL MODE</h1>
              <p style="font-size: 20px;">
                commodo vitae, ornare sit amet, wisi. Aenean fermentum,
                elit eget tincidunt condimentum, eros ipsum rutrum orci,
                </p>
                <span>
              <span class="fa fa-close" style="color: red; font-size: 40px"></span>
                <span style=""> MORE </span>
             </span>
          </div>



      </section>
    </div>
</template>

<script>
export default {
name: "PartFour"
}
</script>

<style scoped>
.Main{
  width: 80%;
  margin: 50px  auto;
}
.Main .Title {
  transform: rotate(-90deg);
  height: 20px;
}
.Main .Title h1 {
  color: red;
  font-weight: bolder;
  font-size: 5rem;
  font-family: 'Bebas Neue';
  letter-spacing: 5px;
  letter-spacing: 30px;

}
/***********************************************************************/
.Main .Image{
  background-image: url("../assets/img-section4.png");
  width: 66vw;
  height: 60vh;

}
.Main .Image img{


}

</style>
