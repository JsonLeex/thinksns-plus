<template>
  <div>
    <ul class="nav nav-tabs component-controller-nav">
      <!-- 广告 -->
      <router-link to="/ad" tag="li" active-class="active">
        <a href="#">广告管理</a>
      </router-link>
      <!-- 统计 -->
      <router-link to="/ad/count" tag="li" active-class="active" exact>
        <a href="#">统计</a>
      </router-link>
    </ul>
    <router-view />
  </div>
</template>