<template>
  <div id="app" style="width: 100%; margin: auto" >
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
  width: 100vw;
  background-color: #d4f4f4;
  padding: 0px;
  margin: 0px;

}
</style>
