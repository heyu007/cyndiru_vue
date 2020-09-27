<template>
  <div class="nav">
    <div class="navbar-wrapper">
      <div class="container-fluid" style="padding:0">
        <nav class="navbar navbar-inverse navbar-static-top">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
              <a class="navbar-brand" href="/web/index">
                <img class="logo" src="__WEB__/picture/logo1.png" alt="">
              </a>
            </div>
            <div id="navbar" class="navbar-collapse collapse">
              <ul class="nav navbar-nav">
                <li><a href="/web/index">首页 / Home-nav</a></li>
                <li><a href="#">关于我们 / About</a></li>
                <li><a href="#">联系我们 / Contact</a></li>
                <li class="dropdown">
                  <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                  <ul class="dropdown-menu">
                    <li><a href="#">Action</a></li>
                    <li><a href="#">Another action</a></li>
                    <li><a href="#">Something else here</a></li>
                    <li role="separator" class="divider"></li>
                    <li class="dropdown-header">Nav header</li>
                    <li><a href="#">Separated link</a></li>
                    <li><a href="#">One more separated link</a></li>
                  </ul>
                </li>
              </ul>

              <!--search start-->
              <div class="navbar-form navbar-right">
                <div class="form-group">
                  <input type="text" class="form-control" id="search" placeholder="Search...">
                </div>
              </div>
              <!--search end-->
            </div>
          </div>
        </nav>
      </div>
    </div>
    <div id="search-result">
      <ul class="list-group" id="search-ul">
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'nav',
  props: {
    msg: ''
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
