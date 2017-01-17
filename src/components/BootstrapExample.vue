<template>
  <div class="container">
    <div class="header clearfix">
      <nav>
        <ul class="nav nav-pills float-right">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </nav>
      <h3 class="text-muted">{{ msg }}</h3>
    </div>

    <div class="jumbotron">
      <h1 class="display-3">Jumbotron heading</h1>
      <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
      <p><a class="btn btn-lg btn-success" href="#" role="button">Sign up today</a></p>
    </div>

    <div class="row marketing">
      <div class="col-lg-6">
        <h4>Subheading</h4>
        <p>Donec id elit non mi porta gravida at eget metus. Maecenas faucibus mollis interdum.</p>

        <h4>Subheading</h4>
        <p>Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Cras mattis consectetur purus sit amet fermentum.</p>

        <h4>Subheading</h4>
        <p>Maecenas sed diam eget risus varius blandit sit amet non magna.</p>
      </div>

      <div class="col-lg-6">
        <h4>Subheading</h4>
        <p>Donec id elit non mi porta gravida at eget metus. Maecenas faucibus mollis interdum.</p>

        <h4>Subheading</h4>
        <p>Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Cras mattis consectetur purus sit amet fermentum.</p>

        <h4>Subheading</h4>
        <p>Maecenas sed diam eget risus varius blandit sit amet non magna.</p>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
        <h1>Bootstrap slider</h1>
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
          <div class="carousel-inner" role="listbox">
            <div class="carousel-item active">
              <div class="d-block">First slide</div>
            </div>
            <div class="carousel-item">
              <div class="d-block">Second slide</div>
            </div>
            <div class="carousel-item">
              <div class="d-block">Third slide</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="footer">
      <p>&copy; Company 2017</p>
    </footer>

  </div>
</template>

<style lang="sass">
 @import "~styles/main.scss"
</style>

<script>
export default {
  name: 'bootsrap-example',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>
