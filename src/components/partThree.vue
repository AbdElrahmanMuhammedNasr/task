<template>
  <div class="row Main">
      <section class="col-sm-5">

        <div class="align-self-center" >
            <p style="font-weight: bolder;
             font-family: 'Bebas Neue';
             letter-spacing: 2px;
              margin: auto">COMPLETE CHALLENGE</p>

            <h1 style="font-family: 'Bebas Neue' ; font-size: 15rem; color: red">13</h1>

          <p style="font-size: 60px;font-family: 'Bebas Neue'">
            You Have
            <br/><span style="color: red ;font-family: 'Bebas Neue'">78%</span><br/>
            chance for survival

          </p>
          <span>
            <span class="fa fa-close" style="color: red; font-size: 40px"></span>
            <span style="font-weight: bolder"> SEE MORE </span>
         </span>
        </div>


      </section>
    
    
      <section class="col-sm-7 row">
        <img  src="../assets/ico_arrow up big white.png" style="width: 150px; height: 150px; transform: rotate(90deg); margin-top: 70%">

        <div >
          <h3 style="font-size: 80px;font-family: 'Bebas Neue'">SHERE YOUR RESULT ON SOCIAL MEDIA</h3>

          <p style="font-size: 20px;">
            commodo vitae, ornare sit amet, wisi. Aenean fermentum,
            elit eget tincidunt condimentum, eros ipsum rutrum orci,
          </p>

          <span>
            <span class="fa fa-close" style="color: red; font-size: 40px"></span>
            <span style=""> SEE RESULT FROM YOUR FRIENDS </span>
         </span>

        </div>




      </section>
  </div>
</template>

<script>
export default {
name: "PartThree"
}
</script>

<style scoped>
.Main{
  width: 80%;
  margin: 10% auto;
}
.Main section:first-child{
  /*background-color: red;*/
}
.Main section:first-child div{
  width: 60%;
  margin: auto;
}
/**********************************************************/
.Main section:nth-child(2){
  background-image: url("../assets/img-section2.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  border-radius: 5px;
  overflow: hidden;
}
.Main section:nth-child(2) div{
  text-align: center;
  color: white;
  width: 60%;
  margin: 10% auto;
  padding: 50px;
  border: 20px solid red;

}

</style>
