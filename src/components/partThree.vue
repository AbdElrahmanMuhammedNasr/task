<template>
  <div class="row Main">
      <section class="col-sm-5">

        <div class="align-self-center" >
            <p style="font-weight: bolder;
             font-family: 'Teko';
             letter-spacing: 2px;
             font-weight: bold;
              margin: auto">COMPLETE CHALLENGE</p>

            <h1 style="font-family: 'Teko' ; font-size: 15rem; color: #E4003B; margin-bottom: -20%">13</h1>

          <p style="font-size: 60px;font-family: 'Teko'; font-weight: bolder">
            You Have
            <br/><span style="color: #E4003B ;font-family: 'Bebas Neue'">78%</span> chance  <br/>
            for survival

          </p>
          <span>
            <span class="fa fa-close" style="color: #E4003B; font-size: 40px"></span>
            <span style="font-weight: bolder"> SEE MORE </span>
         </span>
        </div>


      </section>
    
    
      <section class="col-sm-6 row">
        <img  src="../assets/ico_arrow up big white.png" style="width: 120px; height: 120px; transform: rotate(90deg); margin-top: 73vh">

        <div  style="margin-left: 5%">
          <h3 style="font-size: 80px;font-family: 'Bebas Neue'">SHERE YOUR RESULT ON SOCIAL MEDIA</h3>

          <p style="font-size: 20px;">
            commodo vitae, ornare sit amet, wisi. Aenean fermentum,
            elit eget tincidunt condimentum, eros ipsum rutrum orci,
          </p>

          <span>
            <span class="fa fa-close" style="color: #E4003B; font-size: 40px"></span>
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
  /*background-color: #E4003B;*/
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
  box-shadow: 0px 0px 20px gray;


}
.Main section:nth-child(2) div{
  text-align: center;
  color: white;
  width: 60%;
  margin: 10% auto;
  padding: 50px;
  border: 20px solid #E4003B;

}

</style>
