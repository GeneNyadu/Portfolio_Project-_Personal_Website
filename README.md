# Portfolio_Project-_Personal_Website
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="milestone" content="Portfolio" />
    <title>Genevieve's Portfolio</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css"
    />
    <link href="style.css" rel="stylesheet" />
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">About Me</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#mission-section">Mission</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#skills-section">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact-section">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-content text-center">
        <img src="gene.jpeg" alt="Genevieve Nyadu Headshot" class="headshot" />
        <h1>Genevieve Nyadu</h1>
        <p class="tagline">Web Developer | Designer | Creator</p>
      </div>
    </section>

    <!-- Mission Section -->
    <section id="mission-section" class="container my-5">
      <h2 class="text-center mb-4">Mission</h2>
      <div class="row align-items-center">
        <div class="col-md-6 text-center text-md-start">
          <p>
            I am passionate about crafting beautiful, functional, and
            user-friendly digital experiences that empower individuals and
            organizations to thrive in the digital age. With a focus on
            innovation and creativity, my goal is to develop cutting-edge
            solutions that not only solve real-world problems but also inspire
            and enhance the way people interact with technology. I aim to create
            seamless, intuitive, and impactful designs that make a lasting
            difference in the lives of users, driving both personal growth and
            business success.
          </p>
        </div>
        <div class="col-md-6 text-center">
          <img
            src="women in tech.png"
            alt="Women in Tech"
            class="img-fluid"
            width="700"
          />
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <main>
      <section id="skills-section" class="container my-5">
        <h2 class="text-center mb-4">Skills</h2>
        <div class="row text-center">
          <div class="col-lg-3 col-md-6 mb-4">
            <img
              src="html.png"
              alt="HTML Logo"
              class="img-fluid mb-2"
              width="90"
            />
            <h5>
              Skilled in structuring and organizing web content using HTML5,
              ensuring semantic and accessible layouts with effective use of
              forms, tables, and media.
            </h5>
          </div>
          <div class="col-lg-3 col-md-6 mb-4">
            <img
              src="css.png"
              alt="CSS Logo"
              class="img-fluid mb-2"
              width="70"
            />
            <h5>
              Skilled in using CSS to create visually appealing layouts,
              animations, and responsive designs, leveraging tools like Flexbox
              and Grid for complex structures.
            </h5>
          </div>
          <div class="col-lg-3 col-md-6 mb-4">
            <img
              src="bootstrap-logo-shadow.png"
              alt="Bootstrap Logo"
              class="img-fluid mb-2"
              width="130"
            />
            <h5>
              Proficient in using Bootstrap to build responsive, mobile-friendly
              websites with pre-built components and grid systems for consistent
              design.
            </h5>
          </div>
          <div class="col-lg-3 col-md-6 mb-4">
            <img
              src="java.png"
              alt="JavaScript Logo"
              class="img-fluid mb-2"
              width="90"
            />
            <h5>
              Experienced in object-oriented programming with Java, proficient
              in developing cross-platform applications, algorithms, and
              integrating with databases.
            </h5>
          </div>
        </div>
      </section>

      <!-- Contact Section -->
      <section id="contact-section" class="container my-5">
        <h2 class="text-center mb-4">Contacts</h2>
        <div class="row justify-content-center text-center">
          <div class="col-4 col-md-2 mb-3">
            <a
              href="https://www.linkedin.com/in/genevieve-n-4b9140298"
              target="_blank"
              aria-label="LinkedIn"
            >
              <i class="bi bi-linkedin" style="font-size: 5rem"></i>
            </a>
          </div>
          <div class="col-4 col-md-2 mb-3">
            <a
              href="mailto:genenyadu@gmail.com"
              target="_blank"
              aria-label="Email"
            >
              <i class="bi bi-envelope-at" style="font-size: 5rem"></i>
            </a>
          </div>
          <div class="col-4 col-md-2 mb-3">
            <a
              href="https://www.instagram.com/genevievenyadu/"
              target="_blank"
              aria-label="Instagram"
            >
              <i class="bi bi-instagram" style="font-size: 5rem"></i>
            </a>
          </div>
        </div>
      </section>

      <!-- Footer -->
      <footer class="footer text-center bg-light">
        <p class="mb-0">&copy; Genevieve Nyadu 2025</p>
      </footer>

      <!-- Bootstrap Scripts -->
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </main>
  </body>
</html>

