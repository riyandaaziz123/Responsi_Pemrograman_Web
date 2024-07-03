<template>
  <section class="projects" id="projects">
    <div class="container">
    <div class="col-md-8 col-md-offset-2">
      <div class="heading">
        <h2>MY PROJECT</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3 col-sm-6 col-xs-12 team-main-sec wow slideInUp" data-wow-duration="1s" data-wow-delay=".1s">
        <div class="team-sec">
          <div class="team-img"> <img src="assets/img/hutao.png" class="img-responsive" alt="" height="225px" width="225px">
            <div class="team-desc">
              <h5>Poster hp one plus</h5>
              <p>Merupakan tugas final project mata kuliah komputer grafis</p>
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
          <div class="team-img"> <img src="assets/img/ayaka.png" class="img-responsive" alt="" height="225px" width="225px">
            <div class="team-desc">
              <h5>Poster keycaps ayaka</h5>
              <p>Merupakan tugas final project mata kuliah komputer grafis</p>
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
          <div class="team-img"> <img src="assets/img/tica.png" class="img-responsive" alt="" height="225px" width="225px">
            <div class="team-desc">
              <h5>Desain figma </h5>
              <p>Desain yang dibuat untuk tugas akhir pemrograman web</p>
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
          <div class="team-img"> <img src="assets/img/valo.png" class="img-responsive" alt="" height="225px" width="225px">
            <div class="team-desc">
              <h5>Valorant gaming</h5>
              <p>Perjalanan menuju radint apac</p>
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
  padding: 20px 0;
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
