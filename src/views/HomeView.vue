<script setup>
</script>

<template>
<div class="main">
  <div class="morning">GOOD MORNING</div>
  <form action="search">
    <input type="text" class="search" placeholder="SEARCH" style="background-color: rgb(240, 235, 235);">
  </form>
</div>
<div class="rectangle">
    <div class="rect" style="background: linear-gradient(to bottom right, #ff3300 50%, #ff6600 100%);"></div>
    <div class="rect" style="background: linear-gradient(to top left, #0000cc 2%, #33cccc 100%);"></div>
    <div class="rect" style="background: linear-gradient(to bottom right, #00ff00 0%, #ffff00 100%);"></div>
    <div class="rect" style="background: linear-gradient(to top left, #9900cc 0%, #ff0066 103%);"></div>
</div>
<div class="list">
  <div class="list1" style="padding-right: 6in;">
<div class="listb">
  <div class="listh">Trending</div>
  <div class="listb">
  <ul style="list-style-type: none;">
    <li>MSFT</li>
    <li>AAPPL</li>
    <li>SBUX</li>
  </ul>
  </div>
  </div>
</div>
<div class="listb">
  <div class="listh">Most Searched</div>
  <div class="listb">
  <ul style="list-style-type: none;">
    <li>BRB.A</li>
    <li>KO</li>
    <li>TSL;A</li>
  </ul>
  </div>
  </div>
</div>
</template>

<style scoped>
.morning{
  font-family: roboto;
  font-weight: bold;
  font-size: 1cm;
}
.search{
  height: 5mm;
  width: 7cm;
  border: none;
  margin-top: 3mm;
}
.main{
  display: flex;
  flex-direction: row;
  gap: 100px;
  margin-left: 5cm;
  margin-top: 1cm;
}
.rectangle{
  display: flex;
  flex-direction: row;
  gap: 50px;
  padding-left: 90px;
  padding-top: 50px;
  padding-bottom: 50px;
}
.rect{
  height: 400px;
  width: 250px;
  border-radius: 15px;
}
.list{
  display: flex;
  flex-direction: row;
  font-family: roboto;
  padding-top: 1cm;
  padding-left: 2.5cm;
}
.listh{
  font-weight: bolder;
  font-size: xx-large;
}
.listb{
  font-size: larger;
}
</style>