<template>
  <div class="left-nav">
    <ul>
      <li>
        <i class="icon iconfont icon-wodezichan"></i>
        <div>收银</div>
      </li>
      <li>
        <i class="icon iconfont icon-dianpu"></i>
        <router-link to="Home"><div>店铺</div></router-link>
      </li>
      <li>
        <i class="icon iconfont icon-hanbao"></i>
        <router-link to="Pos"><div>商品</div></router-link>
      </li>
      <li>
        <i class="icon iconfont icon-huiyuanqia"></i>
        <div>会员</div>
      </li>
      <li>
        <i class="icon iconfont icon-tongji"></i>
        <div>统计</div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'leftNav',
  data () {
    return {}
  }
}
</script>
<style>
a,a:link {
  margin:0;
  padding:0;
  border:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
  color: white;
  text-decoration: none;
}
.left-nav {
  color: #fff;
  font-size: 10px;
  height: 100%;
  background-color: #1d8ce0;
  float: left;
  width: 70px;
}
.iconfont {
  font-size: 24px;
}
.left-nav ul {
  padding: 0px;
  margin: 0px;
}
.left-nav li {
  list-style: none;
  text-align: center;
  border-bottom: 1px solid #20a0ff;
  padding: 10px;
}
a {
  text-decoraction: none;
}
.router-link-active,.router-link-hover {
  color: orange;
}
</style>
