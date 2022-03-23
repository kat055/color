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
  <svg width="400" height="600">
    <rect x="60" y="20" rx="30" ry="30" width="200" height="300" style="background: linear-gradient(to bottom right, #ff3300 50%, #ff6600 100%);"/>
  </svg>
  <svg width="400" height="600">
    <rect x="60" y="20" rx="30" ry="30" width="200" height="300" style="background: linear-gradient(to top left, #0000cc 2%, #33cccc 100%);"/>
  </svg>
  <svg width="400" height="600">
    <rect x="60" y="20" rx="30" ry="30" width="200" height="300" style="background: linear-gradient(to bottom right, #00ff00 0%, #ffff00 100%);"/>
  </svg>
  <svg width="400" height="600">
    <rect x="60" y="20" rx="30" ry="30" width="200" height="300" style="background: linear-gradient(to top left, #9900cc 0%, #ff0066 103%);"/>
  </svg>
</div>
<div>
  <table>
    <tr>
      <th>Trending</th>
      <th>Most Searched</th>
    </tr>
    <tr>
      <td>MSFT</td>
      <td>BRB.A</td>
    </tr>
    <tr>
      <td>AAPL</td>
      <td>KO</td>
    </tr>
    <tr>
      <td>SBUX</td>
      <td>TSL;A</td>
    </tr>
  </table>
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
  gap: none;
}
.table th{
  font-family: roboto;
  font-weight: bold;
  font-size: xx-large;
}
</style>