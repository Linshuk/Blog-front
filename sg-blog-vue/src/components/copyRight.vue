<template>
  <div>
    <div class="icp">
      <img src='static/img/icp.png' height="24px">
      <a href="https://beian.mps.gov.cn/#/query/webSearch?code=35012202350308" rel="noreferrer" target="_blank">闽公网安备35012202350308</a>
      <p>闽ICP备2024053769号</p>
      <p>@Copyright Linsk</p>
    </div>

  </div>


</template>

<style>
.icp {
  position: absolute;
  right: 0;
  margin: 10px 0;
  width: 100%;
  height: 24px;
  white-space: pre;
  text-align: center;
  color: gray;
  z-index: 1000;
}
.icp > a {
  color: gray;
  text-decoration: none;
}
.icp > a:hover {
  color: aqua;
  text-decoration: none;
}
</style>
