<template>
  <section class="contact">
    <div id="contact">
        <h2>Contact Me</h2>
        <div id="contact-form">
            <form method="POST" action="https://formspree.io/email@email.com">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Your message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
        <!-- End #contact-form -->
    </div>
    <!-- End #contact -->
    <footer id="footer-down">
      <h2>FOLLOW US ON</h2>
      <ul class="social-icon">
        <li class="facebook hvr-pulse"><a href="#"><i class="fa fa-facebook-f"><img src="assets/img/facebook.png" class="logo" alt=""></i></a></li>
        <li class="twitter hvr-pulse"><a href="#"><i class="fa fa-twitter"><img src="assets/img/twitter.png" class="logo" alt=""></i></a></li>
        <li class="linkedin hvr-pulse"><a href="#"><i class="fa fa-linkedin"><img src="assets/img/linkedin.png" class="logo" alt=""></i></a></li>
        <li class="youtube hvr-pulse"><a href="#"><i class="fa fa-youtube"><img src="assets/img/youtube.png" class="logo" alt=""></i></a></li>
        <li class="instagram hvr-pulse"><a href="#"><i class="fa fa-instagram"><img src="assets/img/instagram.png" class="logo" alt=""></i></a></li>
        <li class="email hvr-pulse"><a href="#"><i class="fa fa-email"><img src="assets/img/email.png" class="logo" alt=""></i></a></li>
      </ul>
    </footer>
    
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 0;
}

#contact {
    padding: 50px 15px;
    background: #f5f5f5;
    text-align: center;

    h2 {
        margin: 0 0 15px 0;
        color: #000000;
        font-weight: 500;
    }
}

#contact-form {
    max-width: 500px;
    margin: 0 auto;

    input, textarea {
        display: block;
        width: 100%;
        padding: 10px;
        border-radius: 4px;
        border: none;
        margin-bottom: 10px;
        background: darken(#fff, 15%);
        color: #000000;
        @include transition();
        @include placeholder {
            color: #fff;
        }

        &:focus {
            outline: none;
            background: darken(#fff, 25%);
        }
    }

    textarea {
        height: 150px;
        resize: none;
    }

    button {
        display: block;
        width: 100%;
        background: #fff;
        border-radius: 4px;
        padding: 5px 10px;
        border: none;
        color: #000;
        font-weight: 700;
        box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
        @include transition();

        &:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
        }
    }
}

#footer {
	text-align:center;
}
#footer .bg-sec h2 {
	color:#FFFFFF;
	font-size:25px;
	font-weight:normal;
}
#footer-down {
	position:relative;
	top:30px;
	text-align:center;
}
#footer-down h2 {
	color:#444;
	margin:20px 0px 40px 0px;
	text-transform:none;
  padding-left: 30px;
}
#footer-down ul li {
	display:inline-block;
	margin-right:30px;
}
#footer-down ul li a i.fa {
	color:#999;
	font-size:22px;
	border:2px solid #999;
	height:50px;
	width:50px;
	border-radius:50px;
	padding:25%;
}

#footer-down ul li.facebook i.fa:hover {
	color:#3b5998;
	border:2px solid #bb0000;
}
#footer-down ul li.twitter i.fa:hover {
	color:#00aced;
	border:2px solid #bb0000;
}
#footer-down ul li.linkedin i.fa:hover {
	color:#007bb6;
	border:2px solid #bb0000;
}
#footer-down ul li.youtube i.fa:hover {
	color:#bb0000;
	border:2px solid #bb0000;
}
#footer-down ul li.instagram i.fa:hover {
	color:#517fa4;
	border:2px solid #bb0000;
}
#footer-down ul li.email i.fa:hover {
	color:#1769ff;
	border:2px solid #bb0000;
}
 .logo {
  width: 30px;
  height: 40px;
  padding-bottom: 10px;
 }
</style>
