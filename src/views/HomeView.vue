<template>
  <!-- Navigation -->
  <nav class="navbar navbar-default navbar-custom navbar-fixed-top">
    <div class="container-fluid">
      <!-- Brand and toggle get grouped for better mobile display -->
      <div class="navbar-header page-scroll">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
          <span class="sr-only">Toggle navigation</span>
          Menu <i class="fa fa-bars"></i>
        </button>
        <a class="navbar-brand" href="index.html">Start Bootstrap</a>
      </div>

      <!-- Collect the nav links, forms, and other content for toggling -->
      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
        <ul class="nav navbar-nav navbar-right">
          <li>
            <a href="index.html">Home</a>
          </li>
          <li>
            <a href="about.html">About</a>
          </li>
          <li>
            <a href="post.html">Sample Post</a>
          </li>
          <li>
            <a href="contact.html">Contact</a>
          </li>
        </ul>
      </div>

    </div>

  </nav>


  <header class="intro-header" style="background-image: url('public/intro.jpg')">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">
          <div class="site-heading">
            <h1>Clean Blog</h1>
            <hr class="small">
            <span class="subheading">A Clean Blog Theme by Start Bootstrap</span>
          </div>
        </div>
      </div>
    </div>
  </header>

</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
