<template>
  <div id="app" style="overflow: hidden" >
    <Header></Header>
    <PartOne></PartOne>
    <PartTwo></PartTwo>
    <PartThree></PartThree>
  </div>
</template>

<script>

import Header from "@/components/header";
import PartOne from "@/components/partOne";
import PartTwo from "@/components/PartTwo";
import PartThree from "@/components/partThree";
export default {
  name: 'App',
  components: {
    Header,
    PartOne,
    PartTwo,
    PartThree,
  }
}
</script>

<style>
#app {
  background-color: #d8efef;
  padding: 0px;
  margin: 0px;

}
::-webkit-scrollbar{
  display: none;
}
</style>
