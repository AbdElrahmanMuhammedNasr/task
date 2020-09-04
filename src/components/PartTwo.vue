<template>
  <div class="row Main">
    <h1 class="col-sm-12">Popular Challenge</h1>

    <section class="col-sm-8 row" >

      <section class="row" v-for="challenge in challenges " :key="challenge.id">
        <div class="col-sm-6">
          <img :src="challenge.image">
        </div>

        <div class="col-sm-5 " style="margin: 2% 0px">
          <p style="color: #E4003B; font-weight: bold">Key Skills</p>
          <h3 style="font-weight: bold ; font-family: 'Bebas Neue';letter-spacing: 2px">{{challenge.name}}</h3>
          <p class="text-muted">{{challenge.details}}</p>
          <span>
                <span class="fa fa-close" style="color: #E4003B; font-size: 30px"></span>
                <span style="font-weight: bolder"> FIND OUT MORE</span>
              </span>
        </div>
      </section>

    </section>


    <section class="col-sm-4" >
      <img src="../assets/img_shoes.png">
        <h3 style="font-weight: bolder ; margin: 20px 0px ;font-family: 'Bebas Neue'; letter-spacing: 2px">Mission</h3>

      <p style="font-weight: bolder ;">
          commodo vitae, ornare sit amet, wisi. Aenean fermentum,
          elit eget tincidunt condimentum,
        </p>

        <p class="text-muted">
          commodo vitae, ornare sit amet, wisi. Aenean fermentum,
          elit eget tincidunt condimentum, eros ipsum rutrum orci,
          sagittis tempus lacus enim ac dui.
        </p>

        <span>
            <span class="fa fa-close" style="color: #E4003B; font-size: 40px"></span>
            <span style="font-weight: bolder"> FIND OUT MORE</span>
         </span>
    </section>

  </div>
</template>

<script>
export default {
  data(){
    return{
      challenges : [
        {
          id:1,
          image :  require('../assets/image-one.png'),
          name:"Fire Making",
          details: ' commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.'
        },
        {
          id:2,
          image :  require('../assets/image-2.png'),
          name:"Make Your Own Shelter",
          details: ' commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.'
        },
        {
          id:3,
          image :  require('../assets/image-3.png'),
          name:"Prepare a Meal",
          details: ' commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.'
        }

      ]
    }
  }
}
</script>

<style scoped>
.Main{
  width: 80%;
  margin: 10% auto;
}
.Main h1 {
    font-size: 3rem;
    font-weight: bolder;
    margin: 30px 0px;
    font-family: 'Teko';
}
.Main section:nth-child(2){

}
.Main section:nth-child(2) section div:first-child img{
  width: 25vw;
  height: 30vh;
  margin-bottom: 20px;
  box-shadow: 0px 0px 20px gray;
  border-radius:5px ;


}
/**************************************************************************/

.Main section:nth-child(3) img {
  width: 100%;

}

</style>
