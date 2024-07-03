<template>
  <section class="projects">
    <div class="container">
    <div class="col-md-8 col-md-offset-2">
      <div class="heading">
        <h2>MY PROJECT</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3 col-sm-6 col-xs-12 team-main-sec wow slideInUp" data-wow-duration="1s" data-wow-delay=".1s">
        <div class="team-sec">
          <div class="team-img"> <img src="assets/img/images.jpg" class="img-responsive" alt="">
            <div class="team-desc">
              <h5>Julia Amanda</h5>
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry</p>
              <ul class="team-social-icon">
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Facebook"><i class="fa fa-facebook-f"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Twitter"><i class="fa fa-twitter"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Pinterest"><i class="fa fa-pinterest-p"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Instagram"><i class="fa fa-instagram"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Google-plus"><i class="fa fa-google-plus"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 team-main-sec wow slideInUp" data-wow-duration="1s" data-wow-delay=".2s">
        <div class="team-sec">
          <div class="team-img"> <img src="assets/img/images.jpg" class="img-responsive" alt="">
            <div class="team-desc">
              <h5>Merry Luis</h5>
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry</p>
              <ul class="team-social-icon">
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Facebook"><i class="fa fa-facebook-f"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Twitter"><i class="fa fa-twitter"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Pinterest"><i class="fa fa-pinterest-p"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Instagram"><i class="fa fa-instagram"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Google-plus"><i class="fa fa-google-plus"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 team-main-sec wow slideInUp" data-wow-duration="1s" data-wow-delay=".3s">
        <div class="team-sec">
          <div class="team-img"> <img src="assets/img/images.jpg" class="img-responsive" alt="">
            <div class="team-desc">
              <h5>Poll Astin</h5>
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry</p>
              <ul class="team-social-icon">
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Facebook"><i class="fa fa-facebook-f"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Twitter"><i class="fa fa-twitter"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Pinterest"><i class="fa fa-pinterest-p"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Instagram"><i class="fa fa-instagram"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Google-plus"><i class="fa fa-google-plus"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 team-main-sec wow slideInUp" data-wow-duration="1s" data-wow-delay=".4s">
        <div class="team-sec">
          <div class="team-img"> <img src="assets/img/images.jpg" class="img-responsive" alt="">
            <div class="team-desc">
              <h5>Janea Syria</h5>
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry</p>
              <ul class="team-social-icon">
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Facebook"><i class="fa fa-facebook-f"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Twitter"><i class="fa fa-twitter"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Pinterest"><i class="fa fa-pinterest-p"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Instagram"><i class="fa fa-instagram"></i></a></li>
                <li><a href="#" data-toggle="tooltip" data-placement="top" title="Google-plus"><i class="fa fa-google-plus"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
  
}

.heading {
	display: flex;
  justify-content: center;
  align-items: center;
  text-align: center; 
	padding-left: 400px;
  padding-bottom: 100px;
}
.team-desc {
	padding:15px 10px 15px 10px;
  
}
.team-desc h2 {
  font-size: 24px;

}
.team-main-sec:hover {
	box-shadow: 0 8px 8px rgba(0, 0, 0, .26);
	-webkit-transition-duration: 0.3s;
	-moz-transition-duration: 0.3s;
	-ms-transition-duration: 0.3s;
	-o-transition-duration: 0.3s;
	transition-duration: 0.3s;
}
.team-sec {
	border:1px solid #eee;
}
.team-main-sec:hover .team-sec {
	border:1px solid #fff;
	-webkit-transition-duration: 0.3s;
	-moz-transition-duration: 0.3s;
	-ms-transition-duration: 0.3s;
	-o-transition-duration: 0.3s;
	transition-duration: 0.3s;
}
.team-main-sec:hover h5 {
	color:#e73131;
}
.team-sec h5 {
	color:#555;
	text-transform:uppercase;
}
.team-social-icon {
	margin-top:20px;
}
.team-desc ul.team-social-icon li {
	display:inline-block;
	padding-right:20px;
}
.team-desc ul.team-social-icon li a i.fa {
	font-size:20px;
	color:#999;
}
.team-desc ul.team-social-icon li a i.fa:hover.fa-facebook-f {
	color:#3b5998;
}
.team-desc ul.team-social-icon li a i.fa:hover.fa-twitter {
	color:#55acee;
}
.team-desc ul.team-social-icon li a i.fa:hover.fa-pinterest-p {
	color:#bd081c;
}
.team-desc ul.team-social-icon li a i.fa:hover.fa-instagram {
	color:#3f729b;
}
.team-desc ul.team-social-icon li a i.fa:hover.fa-google-plus {
	color:#dc4e41;
}
</style>
