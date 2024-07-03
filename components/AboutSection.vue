<template>
  <section class="about" id="about">
    <div class="container">
      <div class="row">
        <div class="col">
          <h2 class="heading">ABOUT</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-4 foto">
          <img src="assets/img/foto.jpeg" class="border" alt="" />
        </div>
        <div class="col-8">
          <p class="paragraf">
            My name is Riyanda Azizi, and I am an Informatics student at Amikom
            University Yogyakarta. I have a deep interest in UI, design, and
            multimedia. With a combination of technical knowledge and
            creativity, I strive to create intuitive and engaging user
            experiences through innovative and functional design. I am always
            eager to learn new things and develop my skills in areas I love.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutSection",
};
</script>

<style scoped>
html {
  scroll-behavior: smooth;
}

.about {
  margin: 10px 0 0 100px;
  padding: 50px 0;
  background: #fff;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.foto {
  margin-top: 50px;
  padding: 20px;
}

.heading {
  font-weight: bold; /* Atur bold pada judul */
  margin-right: 20px;
  padding-right: 40px;
  margin-bottom: 20px; /* Atur jarak antara judul dan isi */
  padding-bottom: 10px;
  justify-content: center;
  text-align: center;
  font-size: 30px; /* Atur ukuran font */
}

.border {
  width: 250px; /* Atur lebar elemen */
  height: 250px; /* Atur tinggi elemen */
  border: 2px solid #ccc; /* Atur ukuran dan warna border */
  border-radius: 50%; /* Membuat border menjadi bulat */
  margin: 0 auto;
}

.paragraf {
  font-size: 18px;
  text-align: justify;
  padding-top: 100px;
  padding-bottom: 50px;
  padding-left: 20px;
  padding-right: 20px;
}

@media (max-width: 768px) {
  .about {
    margin: 50px 0;
    padding: 50px 20px;
  }
  .heading {
    padding-left: 0;
    font-size: 20px; /* Sesuaikan ukuran font untuk layar kecil */
  }
  .paragraf {
    padding-left: 10px;
    padding-right: 10px;
  }
}
</style>
