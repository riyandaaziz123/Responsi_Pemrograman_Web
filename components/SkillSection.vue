<template>
    <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
    <section class="skill" id="skill">
      <div class="container">
        <div class="mytittle">
          <h1 class="title">My Skills</h1>
          <p class="subtitle">Below are some of my technical skills and projects I've worked on.</p>
        </div>
        <div class="main-body">
          <div class="row gutters-sm">
            <div class="col-sm-6 mb-3">
              <div class="card h-100">
                <div class="card-body">
                  <h6 class="d-flex align-items-center mb-3">My skill</h6>
                  <small>Adobe Illustrator</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 70%" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Adobe Photoshop</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 72%" aria-valuenow="72" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Auto Desk Maya</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 89%" aria-valuenow="89" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Figma</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 55%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Front End</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 66%" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-sm-6 mb-3">
              <div class="card h-100">
                <div class="card-body">
                  <h6 class="d-flex align-items-center mb-3">Project Status</h6>
                  <small>Web Design</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Website Markup</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 72%" aria-valuenow="72" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>One Page</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 89%" aria-valuenow="89" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Mobile Template</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 55%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
                  <small>Backend API</small>
                  <div class="progress mb-3" style="height: 5px">
                    <div class="progress-bar bg-primary" role="progressbar" style="width: 66%" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>
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
    name: 'SkillSection',
    // Tambahkan script lainnya jika diperlukan
  }
  </script>
  
  <style scoped>
  .skill {
    margin-top: 40px;
    margin-bottom: 40px;
  }
  .mytittle {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .subtitle {
    font-size: 18px;
  }
  .title, .subtitle {
    text-align: center;
  }
  
  .progress-bar {
    position: relative;
  }
  .bg-primary {
    background-color: #c70101 !important;
  }
  </style>
  