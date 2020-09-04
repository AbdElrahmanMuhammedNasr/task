<template>
  <div id="theNav">
    <nav class="navbar navbar-expand-lg navbar-light " style="background-color: #EDF0F2">
<!--      <a class="navbar-brand  ml-5" href="#">Adventure</a>-->
      <img class="navbar-brand  ml-5" src="../assets/logo.png" style="width: 200px; height: 80px"/>

      <div class="collapse navbar-collapse" >
        <ul class="navbar-nav ml-auto">

          <li class="nav-item active ml-3">
            <a class="nav-link" href="#">OUR COMPETITORS</a>
          </li>

          <li class="nav-item active ml-3">
            <a class="nav-link" href="#">FOR PROFESSIONALS</a>
          </li>

          <li class="nav-item active ml-3">
            <a class="nav-link" href="#">CONTACT</a>
          </li>

          <li class="nav-item active ml-3">
            <a class="nav-link" > | </a>
          </li>

          <li class="nav-item active ml-3">
            <a class="nav-link" href="#">  ENG</a>
          </li>

          <li class="nav-item active ml-3">
            <a class="nav-link" href="#">
              <span class="fa fa-user-circle-o"> </span>
            </a>
          </li>

          <li class="nav-item Search ml-4 mr-4" >
            <a class="nav-link" href="#">
              <span class="fa fa-search"> </span>
            </a>
          </li>


        </ul>

      </div>
    </nav>
  </div>
</template>

<script>

export default {



}
</script>

<style scoped>

    a{
      font-family: 'Teko';
      font-size: 2rem;
    }

    ul li a{
      font-size: 1rem;
      font-family: monospace;
      font-weight: bold;

    }
    span{
      font-size: 20px;
    }
    .Search {
      background-color: #E4003B;
      border-radius:50% ;
    }
    .Search a span{
      color: white;
      font-size: 20px;


    }


</style>
