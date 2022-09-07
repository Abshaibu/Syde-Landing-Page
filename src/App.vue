<script setup>

</script>

<template>
  <header>
    <div class="header-container">
      <div class="logo">
        <a href="#">
          <img alt="SydeInnov logo" class="logo" src="./assets/logo.png" />
        </a>
      </div>
      <div class="header-title">
        <a href="#contact-form">contact us</a>
      </div>
    </div>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero">
      <div>
        <h1>Accelerating Innovation <br class="next-line"> across Africa<span class="dot">.</span></h1>
        <div>
          <p>Lorem ipsum dolor sit amet, consetetur <br class="next-line"> sadipscing elitr, sed diam nonumy eirmod</p>
        </div>
        <div class="scroll-text">
          <p>scroll down</p>
          <img class="arrow-down" src="./assets/arrow-down.svg" alt="a down arrow icon">
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="about-bg">
      <div class="about-us">
      <div class="about-wrapper">
        <div class="about-img">
          <h2>about us.</h2>
          <img src="./assets/virtual-useer.png" alt="a woman at a desk wearing a VR headset">
        </div>
        <div class="about-text">
          <p>
            We are a community of Technology and Engineering enthusiasts that is at the fore front of accelerating the
            adoption of technological advancement in Africa.
          </p>
          <p>
            We do this through building Technological and Engineering Systems ranging from Robotics, Software
            Engineering, Transportation, Green Energy. We explore the use of Computer aided designs tools, programming,
            3D simulation and assembly tools to build basic and large scale industrial designs.
          </p>
          <p class="uppercased">
            Syde-innov will champion the rise of the next generation of designers, that will be responsible for
            designing the Africa of the future.
          </p>
        </div>
      </div>
    </div>
    </section>

    <!-- What We Do -->
    <section class="what-we-do">
      <div class="container">
        <div class="tile-and-description">
          <p>Syde-Innov offers a range of services and opportunities to CAD enthusiasts across the nation.</p>
          <h2>what we do.</h2>
        </div>
        <div class="category-wrapper">
          <div class="category">
            <div class="category-img">
              <img src="./assets/workshop.png" alt="a man working on a desk">
            </div>
            <div class="category-text">
              <h3>workshops</h3>
              <p>Sydeinnov holds fully sponsored yearly technological workshops on Technology , Engineering and design for
                university students starting with Obafemi Awolowo University and planning to expand to 100 other
                institutions across Africa within the next 2 years.</p>
            </div>
          </div>
          <div class="category competition">
            <div class="category-text">
              <h3>competition</h3>
              <p>Sydeinnov trains students fully sponsored and engage them in different Engineering and Design
                competitions like PAADC, Autodesk competition, GrabCAD.</p>
            </div>
            <div class="category-img">
              <img src="./assets/competition.png" alt="a set of persons using computer on a desk">
            </div>
          </div>
          <div class="category">
            <div class="category-img">
              <img src="./assets/mentorship.png" alt="a woman pointing something on a computer">
            </div>
            <div class="category-text">
              <h3>mentorship</h3>
              <p>Sydeinnov leverages the rich tech and engineering ecosystem to bring in leaders in these areas to mentor
                students closely in different areas in software engineering, CAD, PID , Simulation and Assembly.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Meet The Team -->
    <section>
      <div class="container team">
        <h2>meet the team</h2>
        <p>Lorem ipsum dolor sit amet, consetetur</p>
        <div class="team-wrapper">
          <div class="team-member">
            <div class="team-img">
              <img src="./assets/man-posing.png" alt="a man posing for a picture">
            </div>
            <div class="member-details">
              <p>Olawale O.</p>
              <h4>mentor</h4>
            </div>
          </div>
          <div class="team-member">
            <div class="team-img">
              <img src="./assets/man-posing.png" alt="a man posing for a picture">
            </div>
            <div class="member-details">
              <p>Olawale O.</p>
              <h4>mentor</h4>
            </div>
          </div>
          <div class="team-member">
            <div class="team-img">
              <img src="./assets/man-posing.png" alt="a man posing for a picture">
            </div>
            <div class="member-details">
              <p>Olawale O.</p>
              <h4>mentor</h4>
            </div>
          </div>
          <div class="team-member">
            <div class="team-img">
              <img src="./assets/man-posing.png" alt="a man posing for a picture">
            </div>
            <div class="member-details">
              <p>Olawale O.</p>
              <h4>mentor</h4>
            </div>
          </div>
          <div class="team-member">
            <div class="team-img">
              <img src="./assets/man-posing.png" alt="a man posing for a picture">
            </div>
            <div class="member-details">
              <p>Olawale O.</p>
              <h4>mentor</h4>
            </div>
          </div>
        </div>
        <div id="contact-form">
          <h2>contact us</h2>
          <p>Send us a message</p>
          <form action="">
            <div>
              <input type="text" name="first-name" id="fname" placeholder="First name" required>
              <input type="text" name="last-name" id="lname" placeholder="Last name" required>
            </div>
            <div>
              <input type="email" name="email" id="email" placeholder="Phone number" required>
              <input type="text" name="phone" id="phone" placeholder="Email Address" required>
            </div>
            <div><textarea name="message" id="message" placeholder="Enter message here" required></textarea>
            </div>
            <button class="send-btn" type="">
              <span class="btn-text">
                send message
              </span>
            </button>
          </form>
        </div>
      </div>
    </section>
  </main>

  <!--Footer -->
  <footer>
    <div class="header-container">
      <div>
        <small>Copyright © 2021 SydeInnov</small>
      </div>
      <div class="socials">
        <a href="#">
          <img src="./assets/twitter.svg" alt="twitter logo">
        </a>
        <a href="#">
          <img src="./assets/linkedin.svg" alt="linkedin logo">
        </a>
      </div>
    </div>
  </footer>
</template>
