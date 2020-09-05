<template>
    <div class="row Main " >
      <section class="Title col-sm-2  align-self-center"  >
        <h1>ADVICE</h1>
      </section>
      <section class="Image col-sm-10" style="overflow: hidden" >

          <div style="background-color: #EDF0F2;padding: 30px 30px; font-family: 'Teko'; position:absolute; top:0; right: 0 ">
            <h1 class="d-inline p-2" style="border-bottom: 2px solid #E4003B; ">01</h1>
            <h1 style="margin: 20px"></h1>
            <h3 class="d-inline p-2" >03</h3>
          </div>

        <section class="row justify-content-between" style="background-color: red">

          <div  style="background-color: #EDF0F2; width: 25vw; height: 22vh; padding: 30px;position:absolute; bottom:0; left: 0  ">
            <h1  style="font-weight: bolder; font-family: 'Teko'; letter-spacing: 10px">SURVIVAL MODE</h1>
            <p style="font-size: 15px;" >
              commodo vitae, ornare sit amet, wisi. Aenean fermentum,
              elit eget tincidunt condimentum, eros ipsum rutrum orci,
            </p>
            <span>
              <span class="fa fa-close" style="color: #E4003B; font-size: 40px"></span>
                <span style=""> MORE </span>
             </span>
          </div>

          <div style="position:absolute; bottom:0; right: 0" >
            <img class="d-inline p2 "  src="../assets/ico_arrow_white_left.png" style="background-color: #E4003B; padding: 20px">
            <br>
            <img class="d-inline p2"  src="../assets/ico_arrow_black_right.png" style="background-color: white;padding: 20px">
          </div>


        </section>







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
  margin: 10% auto auto auto;
}
.Main .Title {
  transform: rotate(-90deg);
  height: 20px;
}
.Main .Title h1 {
  color: #E4003B;
  font-weight: bolder;
  font-size: 5rem;
  font-family: 'Bebas Neue';
  letter-spacing: 5px;
  letter-spacing: 30px;

}
/***********************************************************************/
.Main .Image{
  background-image: url("../assets/img-section4.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  width: 66vw;
  height: 60vh;
  box-shadow: 0px 0px 20px gray;
  border-radius:10px ;

}
.Main .Image img{


}

</style>
