<template>
  <section class="about">
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h2 class="heading">About Me</h2>
                    <img src="assets/img/images.jpg" class="border" alt="" >
                </div>
                <div class="col-md-8">
                    <p class="paragraf">
                      My name is Riyanda Azizi, and I am an Informatics student at Amikom University Yogyakarta. I have a deep interest in UI, design and multimedia. 
                      With a combination of technical knowledge and creativity, I strive to create intuitive and engaging user experiences through innovative and functional design.
                      I am always eager to learn new things and develop my skills in areas I love.
                    </p>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 50px 0;
  background: #fff;
}
.heading{
  padding-left: 50px;
  padding-bottom: 20px;
}
.border{
  
  width: 250px; /* Atur lebar elemen */
  height: 250px; /* Atur tinggi elemen */
  border: 2px solid #ccc; /* Atur ukuran dan warna border */
  border-radius: 50%; /* Membuat border menjadi bulat */
}
.paragraf{
  font-size: 16px;
  text-align: justify;
  padding-top: 120px;
  padding-bottom: 50px;
  padding-left: 100px;
}

</style>
