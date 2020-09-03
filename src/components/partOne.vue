<template>
  <div class="row">
    <section class="col-sm-3  row ">

      <div>
        <p >Find out if you can</p>
      </div>

      <div >
        <h1>SU</h1>
        <h1>RVI</h1>
        <h1>VE</h1>
      </div>

      <div class="col-sm-12">
        <p class="text-muted">
          Pellentesque habitant morbi tristique
          senectus et netus et malesuada fames ac
          turpis egestas. Vestibulum tortor quam,
          feugiat vitae, ultricies eget, tempor sit amet,
        </p>
      </div>

      <div class="col-sm-12 row">
        <span class="col-sm-12 fa fa-facebook" style="font-size: 25px"></span>
        <span class="col-sm-12 fa fa-youtube" style="font-size: 25px"></span>
        <span class="col-sm-12 fa fa-twitter" style="font-size: 25px"></span>
      </div>

    </section>


    <section class="col-sm-8">
      <img src="https://images.unsplash.com/photo-1491555103944-7c647fd857e6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80">
    </section>

    <section class="col-sm-1  align-self-center">
      <ul class="row">
        <li class="col-sm-12">01</li>
        <li class="col-sm-12">02</li>
        <li class="col-sm-12">03</li>
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
    padding: 0px 2%;
    height: 20vh;

  }
  section:first-child  div:first-child{
    margin-top: 50% ;
    margin-bottom: 20%;
    height: 30px;
    transform: rotate(-90deg);

  }
  section:first-child  div:first-child p {
    font-size: 2rem;
    font-weight: bolder;
  }
  section:first-child div:nth-child(2){
    margin-top: 20% ;
    height: 200px;
  }
  section:first-child div:nth-child(2) h1{
    color: red;
    font-weight: bolder;
    font-size: 5rem;
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

  }

  /************************************************************************/
  section:last-child{
  }

  section:last-child ul {
    margin-top: auto;
    margin-bottom: auto;
  }
  section:last-child ul li{
    font-family: 'Bebas Neue';
    font-weight: bolder;
    font-size: 2rem;
    list-style-type: none;
    float: right;
  }

  section:last-child ul li:first-child{
    font-size: 4rem;
    border-bottom:1px solid red;

  }

</style>
