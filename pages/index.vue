<template>
  <div id="top">
    <!-- test deployment prod -->
    <header>
      <div class="profile-page sidebar-collapse">
        <nav
          class="navbar navbar-expand-lg fixed-top navbar-transparent bg-primary"
          color-on-scroll="400"
        >
          <div class="container" style="padding: 0">
            <div class="navbar-translate">
              <a class="navbar-brand" href="#" rel="tooltip">WISMANNUR</a>
              <button
                class="navbar-toggler navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navigation"
                aria-controls="navigation"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-bar bar1"></span
                ><span class="navbar-toggler-bar bar2"></span
                ><span class="navbar-toggler-bar bar3"></span>
              </button>
            </div>
            <div
              class="collapse navbar-collapse justify-content-end"
              id="navigation"
            >
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link smooth-scroll" href="#about">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link smooth-scroll" href="#skill">Skills</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link smooth-scroll" href="#portfolio">Portfolio</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link smooth-scroll" href="#experience">Experience</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link smooth-scroll" href="#contact">Contact</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
    </header>
    <div class="page-content">
      <div>
        <div class="profile-page">
          <div class="wrapper">
            <div class="page-header page-header-small" filter-color="green">
              <div
                class="page-header-image"
                data-parallax="true"
                style="background-image: url('images/cc-bg-1.jpg')"
              ></div>
              <div
                class="page-header-image"
                data-parallax="true"
                style="background: linear-gradient(0deg, rgba(44, 44, 44, 0.2), rgba(55, 140, 63, 0.6))"
              ></div>
              <div class="container">
                <div class="content-center">
                  <div class="cc-profile-image">
                    <a href="#"><img src="images/wismannur-512x512.jpg" alt="Image" /></a>
                  </div>
                  <div class="h2 title">Wisman Nur Abdul Kholik</div>
                  <p class="category text-white">
                    Full Stack Developer
                  </p>
                  <a
                    class="btn btn-primary smooth-scroll mr-2"
                    href="#contact"
                    data-aos="zoom-in"
                    data-aos-anchor="data-aos-anchor"
                    >Hire Me</a
                  ><a
                    class="btn btn-primary"
                    href="#"
                    data-aos="zoom-in"
                    data-aos-anchor="data-aos-anchor"
                    >Download CV</a
                  >
                </div>
              </div>
              <div class="section">
                <div class="container">
                  <div class="button-container">
                    <a
                      class="btn btn-default btn-round btn-lg btn-icon"
                      href="https://twitter.com/wismannur"
                      rel="tooltip"
                      title="Follow me on Twitter"
                      target="_blank"
                      ><i class="fa fa-twitter"></i></a
                    ><a
                      class="btn btn-default btn-round btn-lg btn-icon"
                      href="https://linkedin.com/in/wismannur"
                      rel="tooltip"
                      title="Follow me on LinkedIn"
                      target="_blank"
                      ><i class="fa fa-linkedin"></i></a
                    ><a
                      class="btn btn-default btn-round btn-lg btn-icon"
                      href="https://www.instagram.com/wismannur"
                      rel="tooltip"
                      title="Follow me on Instagram"
                      target="_blank"
                      ><i class="fa fa-instagram"></i
                    ></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" id="about">
          <div class="container">
            <div class="card" data-aos="fade-up" data-aos-offset="10">
              <div class="row">
                <div class="col-lg-6 col-md-12">
                  <div class="card-body">
                    <div class="h4 mt-0 title">About</div>
                    <p>
                      Hello! I am Wisman Nur a Full Stack Developer.
                    </p>
                    <p>A visionary human who has a dream to become a creator.</p>
                    <p>
                      Has experience in the field of fullstack developer for more than 2 years. I can create a web application from scratch to production. both for the frontend and backend. And also I can deploy an application that I have made to a cloud server such as Apache or Nginx. and not only that, I have experience in developing web applications and identifying, analyzing, and solving problems / errors / bugs. Perform program testing / debugging and special program files. This program is free of bugs. Perform system development / programming.
                    </p>
                  </div>
                </div>
                <div class="col-lg-6 col-md-12">
                  <div class="card-body">
                    <div class="h4 mt-0 title">Basic Information</div>
                    <div class="row">
                      <div class="col-sm-4">
                        <strong class="text-uppercase">Age:</strong>
                      </div>
                      <div class="col-sm-8">{{ age }}</div>
                    </div>
                    <div class="row mt-3">
                      <div class="col-sm-4">
                        <strong class="text-uppercase">Email:</strong>
                      </div>
                      <div class="col-sm-8">
                        <a href="mailto:wismannura@gmail.com" style="color: #000">wismannura@gmail.com</a>
                      </div>
                    </div>
                    <div class="row mt-3">
                      <div class="col-sm-4">
                        <strong class="text-uppercase">Address:</strong>
                      </div>
                      <div class="col-sm-8">
                        Bandung, West Java, Indonesia (ID)
                      </div>
                    </div>
                    <div class="row mt-3">
                      <div class="col-sm-4">
                        <strong class="text-uppercase">Language:</strong>
                      </div>
                      <div class="col-sm-8">Bahasa Indonesia, English, Sundanese</div>
                    </div>
                    <div class="row mt-3">
                      <div class="col-sm-4">
                        <strong class="text-uppercase">My Github:</strong>
                      </div>
                      <div class="col-sm-8">
                        <a href="https://github.com/wismannur" target="_blank" style="color: #000">https://github.com/wismannur</a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" id="skill">
          <div class="container">
            <div class="h4 text-center mb-4 title">Professional Skills</div>
            <div
              class="card"
              data-aos="fade-up"
              data-aos-anchor-placement="top-bottom"
            >
              <div class="card-body">
                <div class="row">
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">HTML</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 80%"
                        ></div>
                        <span class="progress-value">80%</span>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">CSS</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 75%"
                        ></div>
                        <span class="progress-value">75%</span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">JavaScript / Node JS</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 60%"
                        ></div>
                        <span class="progress-value">60%</span>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">SASS</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 60%"
                        ></div>
                        <span class="progress-value">60%</span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">TypeScript</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 60%"
                        ></div>
                        <span class="progress-value">60%</span>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">Bootstrap</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 70%"
                        ></div>
                        <span class="progress-value">70%</span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">Vue JS</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 70%"
                        ></div>
                        <span class="progress-value">70%</span>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="progress-container progress-primary">
                      <span class="progress-badge">Angular JS</span>
                      <div class="progress">
                        <div
                          class="progress-bar progress-bar-primary"
                          data-aos="progress-full"
                          data-aos-offset="10"
                          data-aos-duration="2000"
                          role="progressbar"
                          aria-valuenow="60"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          style="width: 70%"
                        ></div>
                        <span class="progress-value">70%</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" id="portfolio">
          <div class="container">
            <div class="row">
              <div class="col-md-6 ml-auto mr-auto">
                <div class="h4 text-center mb-4 title">Portfolio</div>
                <div class="nav-align-center">
                  <ul class="nav nav-pills nav-pills-primary" role="tablist">
                    <li class="nav-item">
                      <a
                        class="nav-link active"
                        data-toggle="tab"
                        href="#web-development"
                        role="tablist"
                        ><i class="fa fa-laptop" aria-hidden="true"></i
                      ></a>
                    </li>
                    <li class="nav-item">
                      <a
                        class="nav-link"
                        data-toggle="tab"
                        href="#graphic-design"
                        role="tablist"
                        ><i class="fa fa-picture-o" aria-hidden="true"></i
                      ></a>
                    </li>
                    <li class="nav-item">
                      <a
                        class="nav-link"
                        data-toggle="tab"
                        href="#Photography"
                        role="tablist"
                        ><i class="fa fa-camera" aria-hidden="true"></i
                      ></a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="tab-content gallery mt-5">
              <div class="tab-pane active" id="web-development">
                <div class="ml-auto mr-auto">
                  <div class="row">
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#web-development">
                          <figure class="cc-effect">
                            <img src="images/project-1.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Recent Project</div>
                              <p>Web Development</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#web-development">
                          <figure class="cc-effect">
                            <img src="images/project-2.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Startup Project</div>
                              <p>Web Development</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#web-development">
                          <figure class="cc-effect">
                            <img src="images/project-3.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Food Order Project</div>
                              <p>Web Development</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#web-development">
                          <figure class="cc-effect">
                            <img src="images/project-4.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Web Advertising Project</div>
                              <p>Web Development</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="tab-pane" id="graphic-design" role="tabpanel">
                <div class="ml-auto mr-auto">
                  <div class="row">
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#graphic-design">
                          <figure class="cc-effect">
                            <img
                              src="images/graphic-design-1.jpg"
                              alt="Image"
                            />
                            <figcaption>
                              <div class="h4">Triangle Pattern</div>
                              <p>Graphic Design</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#graphic-design">
                          <figure class="cc-effect">
                            <img
                              src="images/graphic-design-2.jpg"
                              alt="Image"
                            />
                            <figcaption>
                              <div class="h4">Abstract Umbrella</div>
                              <p>Graphic Design</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#graphic-design">
                          <figure class="cc-effect">
                            <img
                              src="images/graphic-design-3.jpg"
                              alt="Image"
                            />
                            <figcaption>
                              <div class="h4">Cube Surface Texture</div>
                              <p>Graphic Design</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#graphic-design">
                          <figure class="cc-effect">
                            <img
                              src="images/graphic-design-4.jpg"
                              alt="Image"
                            />
                            <figcaption>
                              <div class="h4">Abstract Line</div>
                              <p>Graphic Design</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="tab-pane" id="Photography" role="tabpanel">
                <div class="ml-auto mr-auto">
                  <div class="row">
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#Photography">
                          <figure class="cc-effect">
                            <img src="images/photography-1.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Photoshoot</div>
                              <p>Photography</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#Photography">
                          <figure class="cc-effect">
                            <img src="images/photography-3.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Wedding Photoshoot</div>
                              <p>Photography</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#Photography">
                          <figure class="cc-effect">
                            <img src="images/photography-2.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Beach Photoshoot</div>
                              <p>Photography</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                      <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                      >
                        <a href="#Photography">
                          <figure class="cc-effect">
                            <img src="images/photography-4.jpg" alt="Image" />
                            <figcaption>
                              <div class="h4">Nature Photoshoot</div>
                              <p>Photography</p>
                            </figcaption>
                          </figure>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" id="experience">
          <div class="container cc-experience">
            <div class="h4 text-center mb-4 title">Work Experience</div>
            <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-experience-header">
                    <p>Jun 2019 - Present</p>
                    <div class="h5">BIT - Barito Technologies Group</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Full Stack Developer</div>
                    <p>
                      As a Frontend Developer here I am building a mobile application with my good team, the PRU-Force activity management application. <br>
                      - Front End Development : ReactJS, HTML, CSS, Vanilla JS, LESS, Responsive Design Application. <br>
                      <br>
                      As a Full Stack Developer here I am building a back office application with my good team, the PRUHub Leads Management application. <br>
                      - Front End Development : AngularJS, Ionic, Typescript, HTML, CSS, SCSS, Responsive web Design Application. <br>
                      - Back End Development : Java, SpringBoot, PostgreSQL.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-experience-header">
                    <p>Nov 2018 - Jun 2019</p>
                    <div class="h5">Arisoft Riset Informatika</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Full Stack Developer</div>
                    <p class="category">Bandung Area, West Java, Indonesia (ID)</p>
                    <p>
                      - Identifying, analyzing and solving the problems/errors/bugs <br>
                      - Performing program test/debugging and make sure program free of bugs  <br>
                      - Performing system development/programming <br>
                      - Front End development : HTML, CSS, SCSS, Twig, Jquery, Jquery UI, JavaScript, Bootstrap. <br>
                      - Back End development: Python Django, PHP. <br>
                      - Database development : PostgreSql, MySQL, MariaDB. <br>
                      - Webserver development : Nginx, Apache, Linux Ubuntu.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-experience-header">
                    <p>Feb 2018 - Sep 2018</p>
                    <div class="h5">Navcore Nextology</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Full Stack Developer</div>
                    <p class="category">Greater Jakarta Area, Indonesia (ID)</p>
                    <p>
                      I developed a DCN product (Distributed Channel Network) with my team, products for flight ticket reservations and Hajj and Umrah departures, using Nexigo internal framework.
                      <br>
                      - Front End development : HTML, CSS, JavaScript, JQUERY, AJAX, Kendo Grid. <br>
                      - Back End development : Golang. <br>
                      - Database Development : Nexigo API, PostgreSQL.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section">
          <div class="container cc-education">
            <div class="h4 text-center mb-4 title">Education</div>
            <!-- <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-education-header">
                    <p>2013 - 2015</p>
                    <div class="h5">Master's Degree</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Master of Information Technology</div>
                    <p class="category">University of Computer Science</p>
                    <p>
                      Euismod massa scelerisque suspendisse fermentum habitant
                      vitae ullamcorper magna quam iaculis, tristique sapien
                      taciti mollis interdum sagittis libero nunc inceptos
                      tellus, hendrerit vel eleifend primis lectus quisque
                      cubilia sed mauris. Lacinia porta vestibulum diam integer
                      quisque eros pulvinar curae, curabitur feugiat arcu
                      vivamus parturient aliquet laoreet at, eu etiam pretium
                      molestie ultricies sollicitudin dui.
                    </p>
                  </div>
                </div>
              </div>
            </div> -->
            <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-education-header">
                    <p>Nov 2017 - Jan 2018</p>
                    <div class="h5">Bootcamp</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Bootcamp Full Stack Academy</div>
                    <p class="category">Makers Institute Indonesia</p>
                    <p>
                      Euismod massa scelerisque suspendisse fermentum habitant
                      vitae ullamcorper magna quam iaculis, tristique sapien
                      taciti mollis interdum sagittis libero nunc inceptos
                      tellus, hendrerit vel eleifend primis lectus quisque
                      cubilia sed mauris. Lacinia porta vestibulum diam integer
                      quisque eros pulvinar curae, curabitur feugiat arcu
                      vivamus parturient aliquet laoreet at, eu etiam pretium
                      molestie ultricies sollicitudin dui.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="row">
                <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body cc-education-header">
                    <p>2014 - 2017</p>
                    <div class="h5">Vocational High School</div>
                  </div>
                </div>
                <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
                >
                  <div class="card-body">
                    <div class="h5">Computer and Network Engineering</div>
                    <p class="category">School of SMK Penida 2 Katapang</p>
                    <p>
                      Euismod massa scelerisque suspendisse fermentum habitant
                      vitae ullamcorper magna quam iaculis, tristique sapien
                      taciti mollis interdum sagittis libero nunc inceptos
                      tellus, hendrerit vel eleifend primis lectus quisque
                      cubilia sed mauris. Lacinia porta vestibulum diam integer
                      quisque eros pulvinar curae, curabitur feugiat arcu
                      vivamus parturient aliquet laoreet at, eu etiam pretium
                      molestie ultricies sollicitudin dui.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- <div class="section" id="reference">
          <div class="container cc-reference">
            <div class="h4 mb-4 text-center title">References</div>
            <div class="card" data-aos="zoom-in">
              <div
                class="carousel slide"
                id="cc-Indicators"
                data-ride="carousel"
              >
                <ol class="carousel-indicators">
                  <li
                    class="active"
                    data-target="#cc-Indicators"
                    data-slide-to="0"
                  ></li>
                  <li data-target="#cc-Indicators" data-slide-to="1"></li>
                  <li data-target="#cc-Indicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <div class="row">
                      <div class="col-lg-2 col-md-3 cc-reference-header">
                        <img src="images/reference-image-1.jpg" alt="Image" />
                        <div class="h5 pt-2">Aiyana</div>
                        <p class="category">CEO / WEBM</p>
                      </div>
                      <div class="col-lg-10 col-md-9">
                        <p>
                          Habitasse venenatis commodo tempor eleifend arcu
                          sociis sollicitudin ante pulvinar ad, est porta cras
                          erat ullamcorper volutpat metus duis platea convallis,
                          tortor primis ac quisque etiam luctus nisl nullam
                          fames. Ligula purus suscipit tempus nascetur curabitur
                          donec nam ullamcorper, laoreet nullam mauris dui
                          aptent facilisis neque elementum ac, risus semper
                          felis parturient fringilla rhoncus eleifend.
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <div class="row">
                      <div class="col-lg-2 col-md-3 cc-reference-header">
                        <img src="images/reference-image-2.jpg" alt="Image" />
                        <div class="h5 pt-2">Braiden</div>
                        <p class="category">CEO / Creativem</p>
                      </div>
                      <div class="col-lg-10 col-md-9">
                        <p>
                          Habitasse venenatis commodo tempor eleifend arcu
                          sociis sollicitudin ante pulvinar ad, est porta cras
                          erat ullamcorper volutpat metus duis platea convallis,
                          tortor primis ac quisque etiam luctus nisl nullam
                          fames. Ligula purus suscipit tempus nascetur curabitur
                          donec nam ullamcorper, laoreet nullam mauris dui
                          aptent facilisis neque elementum ac, risus semper
                          felis parturient fringilla rhoncus eleifend.
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <div class="row">
                      <div class="col-lg-2 col-md-3 cc-reference-header">
                        <img src="images/reference-image-3.jpg" alt="Image" />
                        <div class="h5 pt-2">Alexander</div>
                        <p class="category">CEO / Webnote</p>
                      </div>
                      <div class="col-lg-10 col-md-9">
                        <p>
                          Habitasse venenatis commodo tempor eleifend arcu
                          sociis sollicitudin ante pulvinar ad, est porta cras
                          erat ullamcorper volutpat metus duis platea convallis,
                          tortor primis ac quisque etiam luctus nisl nullam
                          fames. Ligula purus suscipit tempus nascetur curabitur
                          donec nam ullamcorper, laoreet nullam mauris dui
                          aptent facilisis neque elementum ac, risus semper
                          felis parturient fringilla rhoncus eleifend.
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div> -->
        <div class="section" id="contact">
          <div
            class="cc-contact-information"
            style="background-image: url('images/maps-bandung.JPG')"
          >
            <div class="container">
              <div class="cc-contact">
                <div class="row">
                  <div class="col-md-9">
                    <div class="card mb-0" data-aos="zoom-in">
                      <div class="h4 text-center title">Contact Me</div>
                      <div class="row">
                        <div class="col-md-6">
                          <div class="card-body">
                            <form
                              action="https://formspree.io/your@email.com"
                              method="POST"
                            >
                              <div class="p pb-3">
                                <strong>Feel free to contact me </strong>
                              </div>
                              <div class="row mb-3">
                                <div class="col">
                                  <div class="input-group">
                                    <span class="input-group-addon">
                                      <i class="fa fa-user-circle"></i>
                                    </span>
                                    <input
                                      class="form-control"
                                      type="text"
                                      name="name"
                                      placeholder="Name"
                                      required="required"
                                    />
                                  </div>
                                </div>
                              </div>
                              <div class="row mb-3">
                                <div class="col">
                                  <div class="input-group">
                                    <span class="input-group-addon">
                                      <i class="fa fa-file-text"></i>
                                    </span>
                                    <input
                                      class="form-control"
                                      type="text"
                                      name="Subject"
                                      placeholder="Subject"
                                      required="required"
                                    />
                                  </div>
                                </div>
                              </div>
                              <div class="row mb-3">
                                <div class="col">
                                  <div class="input-group">
                                    <span class="input-group-addon">
                                      <i class="fa fa-envelope"></i>
                                    </span>
                                    <input
                                      class="form-control"
                                      type="email"
                                      name="_replyto"
                                      placeholder="E-mail"
                                      required="required"
                                    />
                                  </div>
                                </div>
                              </div>
                              <div class="row mb-3">
                                <div class="col">
                                  <div class="form-group">
                                    <textarea
                                      class="form-control"
                                      name="message"
                                      placeholder="Your Message"
                                      required="required"
                                    ></textarea>
                                  </div>
                                </div>
                              </div>
                              <div class="row">
                                <div class="col">
                                  <button class="btn btn-primary">
                                    Send
                                  </button>
                                </div>
                              </div>
                            </form>
                          </div>
                        </div>
                        <div class="col-md-6">
                          <div class="card-body">
                            <p class="mb-0"><strong>Address </strong></p>
                            <p class="pb-2">
                              Bandung, West Java, Indonesia (ID)
                            </p>
                            <p class="mb-0"><strong>Email</strong></p>
                            <a href="mailto:wismannura@gmail.com" style="color: #000"><p class="pb-2" >wismannura@gmail.com</p></a>
                            <p class="mb-0"><strong>Send Message in LinkedIn</strong></p>
                            <a href="https://linkedin.com/in/wismannur" target="_blank" style="color: #000"><p class="pb-2">https://linkedin.com/in/wismannur</p></a>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="container text-center">
        <a class="cc-twitter btn btn-link" href="https://twitter.com/wismannur" target="_blank">
          <i class="fa fa-twitter fa-2x" aria-hidden="true"></i>
        </a>
        <a class="cc-linkedin btn btn-link" href="https://linkedin.com/in/wismannur" target="_blank">
          <i class="fa fa-linkedin fa-2x" aria-hidden="true"></i>
        </a>
        <a class="cc-instagram btn btn-link" href="https://www.instagram.com/wismannur" target="_blank">
          <i class="fa fa-instagram fa-2x" aria-hidden="true"></i>
        </a>
      </div>
      <div class="h4 title text-center">Wisman Nur Abdul Kholik</div>
      <div class="text-center text-muted">
        <p>
          &copy; Creative CV. All rights reserved.<br />Design -
          <a class="credit" href="https://templateflip.com" style="color: #000" target="_blank">TemplateFlip</a>
        </p>
      </div>
    </footer>

    <script src="/js/core/jquery.3.2.1.min.js" />
    <script src="/js/core/popper.min.js" />
    <script src="/js/core/bootstrap.min.js" />
    <script src="/js/now-ui-kit.js?v=1.1.0" />
    <script src="/js/aos.js" />
    <script src="/js/main.js" />
  </div>
</template>

<script>
export default {
  layout: 'resume',
  data () {
    return {
      age: this.calculateAge(new Date(1999, 3, 28))
    }
  },
  methods: {
    calculateAge (dob) {
      const diffMs = Date.now() - dob.getTime()
      const ageDt = new Date(diffMs)
      return Math.abs(ageDt.getUTCFullYear() - 1970)
    }
  },
  head () {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: 'https://fonts.googleapis.com/css?family=Montserrat:400,700,200'
        },
        {
          rel: 'stylesheet',
          href: 'https://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css'
        },
        { rel: 'stylesheet', href: '/css/aos.css' },
        { rel: 'stylesheet', href: '/css/bootstrap.min.css' },
        { rel: 'stylesheet', href: '/css/main.css' }
      ],
      script: []
    }
  }
}
</script>

<style scoped>
.cc-contact-information {
  background-size: cover;
}
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>
