<template>
  <div id="app" style="overflow: hidden" >
    <Header style="position: fixed; z-index: 1000; width: 100%;    "></Header>
    <PartOne style="margin-top: 85px"></PartOne>
    <PartTwo></PartTwo>
    <PartThree></PartThree>
    <PartFour></PartFour>
    <PartSix></PartSix>
  </div>
</template>

<script>

import Header from "@/components/header";
import PartOne from "@/components/partOne";
import PartTwo from "@/components/PartTwo";
import PartThree from "@/components/partThree";
import PartFour from "@/components/partFour";
import PartSix from "@/components/partSix";
export default {
  name: 'App',
  components: {
    Header,
    PartOne,
    PartTwo,
    PartThree,
    PartFour,
    PartSix
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
