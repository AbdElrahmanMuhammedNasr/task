<template>
    <div class="row Main " >
      <section class="Title col-sm-2  align-self-center"  >
        <h1>ADVICE</h1>
      </section>
      <section class="Image col-sm-10" style="overflow: hidden" >

        <div class="row"  style="  width: 10%;  float: right; ">
          <div style="background-color: #d8efef;padding: 30px 30px; font-family: 'Teko';position: relative; right: -20%">
            <h1 class="d-inline p-2" style="border-bottom: 2px solid red; ">01</h1>
            <h1 style="margin: 20px"></h1>
            <h3 class="d-inline p-2" >03</h3>
          </div>


          <div style="position: relative;margin-top: 32vh; right: -50% ">
            <img class="d-inline p2 "  src="../assets/ico_arrow_white_left.png" style="background-color: red; padding: 20px">
            <br>
            <img class="d-inline p2"  src="../assets/ico_arrow_black_right.png" style="background-color: white;padding: 20px">
          </div>
        </div>
        

          <div  style="background-color: #d8efef; width: 25vw; padding: 30px;position: relative; top: 65%; left: -20px  ">
            <h1  style="font-weight: bolder; font-family: 'Teko'; letter-spacing: 10px">SURVIVAL MODE</h1>
            <p style="font-size: 15px;" >
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
  margin: 100px  auto;
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
