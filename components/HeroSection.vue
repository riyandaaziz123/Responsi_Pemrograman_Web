<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <header class="navbar">
        <div class="navbar__container">
            <div class="navbar__logo"></div>
            <nav class="navbar__menu">
                <a href="#home-hero" class="navbar__link">Home</a>
                <a href="#about" class="navbar__link">About</a>
                <a href="#projects" class="navbar__link">Project</a>
                <a href="#contact" class="navbar__link">Contact</a>
            </nav>
        </div>
    </header>
    <section id="home-hero" class="home-hero">
    <div class="home-hero__content">
      <div class="home-hero__info">
        <div class="profile">
          <img src="assets/img/pp.jpeg" alt="">
        </div>
        <h1 class="heading-primary home-hero__heading-primary">
          <span class="heading-primary__main">
            I'M RIYANDA AZIZI
          </span><br>
          <span class="heading-primary__main">
            Web Developer, UI/UX Designer, Freelancer
          </span>
        </h1>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>
<style scoped>
/* Styles for the home hero section */
/* Styles for the home hero section */
.home-hero {
  position: relative; /* Ensure pseudo-element is positioned correctly */
  display: flex;
  align-items: center; /* Center content vertically */
  justify-content: center; /* Center content horizontally */
  min-height: 100vh; /* Full viewport height */
  background: #f5f5f5; /* Example background color */
  background-image: url('assets/img/bg.jpg'); /* Path to your background image */
  background-repeat: no-repeat; /* Ensure the background image does not repeat */
  background-size: cover; /* Cover the entire hero section with the background image */
  background-position: center; /* Center the background image */
  padding: 2rem; /* Add some padding for spacing */
  z-index: 1; /* Ensure content is above the pseudo-element */
}

.home-hero::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5); /* Black background with 50% opacity */
  z-index: -1; /* Place the pseudo-element behind the content */
}

.home-hero__content {
  max-width: 1200px; /* Max width for content */
  width: 100%;
  text-align: center; /* Center text */
  animation: downToUp 0.8s; /* Add your animation */
  margin: auto; /* Center content horizontally */
  position: relative; /* Ensure content is above the pseudo-element */
  z-index: 2; /* Ensure content is above the pseudo-element */
}

@media (max-width: 768px) { /* Media query for smaller screens */
  .home-hero {
    padding: 4rem 1rem; /* Adjust padding for smaller screens */
  }

  .home-hero__content {
    padding: 15rem 0 10rem 0; /* Adjust padding for smaller screens */
  }
}

.home-hero__heading-primary {
  margin-bottom: 2rem;
  font-size: 3rem; /* Example font size, adjust as needed */
  color: #fff;
}

.home-hero__btn-theme {
  margin-right: 1rem;
  padding: 1rem 2rem; /* Example padding, adjust as needed */
}

@media (max-width: 768px) {
  .home-hero__heading-primary {
    margin-bottom: 1.5rem;
    font-size: 2.5rem; /* Smaller font size for smaller screens */
  }

  .home-hero__btn-theme,
  .home-hero__btn-inv {
    width: 100%; /* Full width buttons on smaller screens */
    padding: 1rem; /* Adjust padding for smaller screens */
  }

  .home-hero__btn-theme {
    margin: 0 0 2rem 0; /* Adjust margin for smaller screens */
  }
}

/* Example keyframes for the downToUp animation */
@keyframes downToUp {
  from {
    opacity: 0;
    transform: translateY(50px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
.profile {
  display: flex;
  justify-content: center; /* Center the image horizontally */
  align-items: center; /* Center the image vertically if needed */
  height: 100%; /* Ensure the container has height */
  padding-bottom: 80PX;
}

.profile img {
  width: 150px; /* Set the width of the image */
  height: 150px; /* Set the height of the image */
  border-radius: 50%; /* Make the image circular */
  object-fit: cover; /* Ensure the image covers the entire area */
}


.navbar {
    background-color: #c70101;
    color: #fff;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.navbar__container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.navbar__logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.navbar__menu {
    display: flex;
}

.navbar__link {
    color: #fff;
    padding: 0.75rem 1.5rem;
    transition: background-color 0.3s;
}

.navbar__link:hover {
    background-color: #1a1a1a;
    border-radius: 4px;
}

/* Responsive styles */
@media (max-width: 768px) {
    .navbar__container {
        flex-direction: column;
    }

    .navbar__menu {
        flex-direction: column;
        width: 100%;
    }

    .navbar__link {
        width: 100%;
        text-align: center;
    }
}
</style>
