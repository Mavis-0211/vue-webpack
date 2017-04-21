<template>
  <div id="wrapper">
    <nav class="navbar navbar-default">
      <div class="container">
        <a href="#" class="navbar-brand">
          <i class="glyphicon glyphicon-bookmark"></i>
          <span>myBlog</span>
        </a>
        
        <!-- 未登录状态 -->
        <!--<ul class="nav navbar-nav navbar-right">
          <li><router-link to="/">登录</router-link></li>
          <li><router-link to="/">注册</router-link></li>
        </ul>-->
        
        <!-- 已登录状态 -->
        <ul class="nav navbar-nav">
          <li class="active"><router-link to="/">社区</router-link></li>
          <li><router-link to="/">发表</router-link></li>
        </ul>
        <ul class="nav navbar-nav navbar-right">
          <li><router-link to="/">my</router-link></li>
          <li><router-link to="/">退出</router-link></li>
        </ul>
      </div>
    </nav>
  </div>
</template>

