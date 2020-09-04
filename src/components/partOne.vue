
<template>
  <div class="row">
    <section class="col-sm-3  row ">

      <div class="col-sm-8; align-self-center" style="">
        <p >Find out if you can</p>
      </div>

      <div class="col-sm-2 ; align-self-center " style="margin-left: -20%">
        <h1>SU</h1>
        <h1>RVI</h1>
        <h1>VE</h1>
      </div>

      <div class="col-sm-12" style="padding-left: 13% ; margin-top: 3vh">
        <p class="text-muted" >
          Pellentesque habitant morbi tristique
          senectus et netus et malesuada fames ac
        </p>
      </div>

      <div class="col-sm-12 row"  style="padding-left: 22%;margin-top: -15vh ; ">
        <ul>
          <li class="col-sm-12 fa fa-facebook" style="margin: 10px 0px; font-size: 20px"></li>
          <li class="col-sm-12 fa fa-twitter" style="margin: 10px 0px;font-size: 20px"></li>
          <li class="col-sm-12 fa fa-youtube" style="margin: 10px 0px;font-size: 20px"></li>
        </ul>
      </div>

    </section>


    <section class="col-sm-8">
      <img src="../assets/slider-image.png">
    </section>

    <section class="col-sm-1  align-self-center">
      <ul class="row">
        <li class="col-sm-12">01</li>
        <li class="col-sm-12" style="margin: 10px 50px">02</li>
        <li class="col-sm-12" style="margin: 10px 50px">03</li>
      </ul>

    </section>

  </div>
</template>

<script>

export default {
name: "partOne"
}
</script>

<style scoped>
  section:first-child{
    padding: 0px 3%;
    height: auto;

  }
  section:first-child  div:first-child{
    margin-top: 50% ;
    margin-bottom: 20%;
    height: 30px;
    transform: rotate(-90deg);

  }
  section:first-child  div:first-child p {
    font-size: 1.5rem;
    font-weight: bolder;

  }
  section:first-child div:nth-child(2){
    margin-top: 20% ;
    height: 200px;

  }
  section:first-child div:nth-child(2) h1{
    color: #E4003B;
    font-weight: bolder;
    font-size: 7rem;
    margin-top: -40px;
    font-family: 'Teko';

  }
  section:first-child div:nth-child(3){
    float: right;
    margin:110px 0px 0px 0px ;
  }

  section:first-child div:nth-child(3) p{
    padding-left:100px ;

  }
  section:first-child div:nth-child(4) {
    padding: 20px;

  }
  section:first-child div:nth-child(4) span{
    margin-top: 15px;
    cursor: pointer;
  }
    /************************************************************************/
  section:nth-child(2){
  }
  section:nth-child(2) img{
    width: 100%;
    box-shadow: 0px 0px 20px gray;


  }

  /************************************************************************/
  section:last-child{
  }

  section:last-child ul {
    float: left;
    padding: 20px;

  }
  section:last-child ul li{
    font-family: 'Teko';
    font-weight: bolder;
    font-size: 1.5rem;
    list-style-type: none;

  }

  section:last-child ul li:first-child{
    font-size: 4rem;
    border-bottom:3px solid #E4003B;

  }

</style>
