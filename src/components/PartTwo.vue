<template>
  <div class="row Main">
    <h1 class="col-sm-12">Popular Challenge</h1>

    <section class="col-sm-8 row" >

      <section class="row" v-for="challenge in challenges " :key="challenge.name">
        <div class="col-sm-5">
          <img :src="challenge.image">
        </div>

        <div class="col-sm-5 " style="margin: 2% 0px">
          <p style="color: red; font-weight: bold">Key Skills</p>
          <h3 style="font-weight: bold ; font-family: 'Bebas Neue';letter-spacing: 2px">{{challenge.name}}</h3>
          <p class="text-muted">{{challenge.details}}</p>
          <span>
                <span class="fa fa-close" style="color: red; font-size: 30px"></span>
                <span style="font-weight: bolder"> FIND OUT MORE</span>
              </span>
        </div>
      </section>

    </section>


    <section class="col-sm-4" >
      <img src="https://images.unsplash.com/photo-1556048219-bb6978360b84?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=60">
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
            <span class="fa fa-close" style="color: red; font-size: 40px"></span>
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
          image :  "https://images.unsplash.com/photo-1552571219-d6e38a3f4849?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80",
          name:"Fire Making",
          details: ' commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.'
        },
        {
          image :  "https://images.unsplash.com/photo-1552931668-b6fedfb82b1a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=60",
          name:"Make Your Own Shelter",
          details: ' commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.'
        },
        {
          image :  "https://images.unsplash.com/photo-1551207004-3e38b4f52ba6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=60",
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
}
.Main section:nth-child(2){

}
.Main section:nth-child(2) section div:first-child img{
  width: 400px;
  height: 300px;
  margin-bottom: 20px;
}
/**************************************************************************/

.Main section:nth-child(3) img {
  width: 100%;
}

</style>
