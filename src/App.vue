<template>
  <div class="hero">
    <header
      class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 fw-bold container"
    >
      <div class="col-md-3 mb-2 mb-md-0 justify-content-start">
        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
          <img src="https://don.finding.lk/images/rentalize_logo.png" width="140" />
        </a>
      </div>
      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
        <li><a href="#" class="nav-link px-4">Home</a></li>
        <li><a href="#features" class="nav-link px-4" v-smooth-scroll>Features</a></li>
        <li><a href="#whyus" class="nav-link px-4" v-smooth-scroll>Why Us</a></li>
        <li><a href="#price" class="nav-link px-4" v-smooth-scroll>Pricing</a></li>
        <li><a href="#feedback" class="nav-link px-4" v-smooth-scroll>Feedback</a></li>
      </ul>

      <div class="col-md-3 text-end">
        <button type="button" class="btn me-2 text-theme">login</button>
        <button type="button" class="btn btn-primary rounded-pill">
          Sign up- It’s Free
        </button>
      </div>
    </header>

    <section class="py-lg-16 py-5 position-relative overflow-hidden">
      <div class="container position-relative zi-2">
        <div class="row align-items-center">
          <div class="col-lg-6 mb-6 mb-lg-0">
            <div class="">
              <h5 class="text-dark mb-4">
                <i
                  class="fe fe-check icon-xxs icon-shape bg-light-success text-success rounded-circle me-2"
                ></i
                >Offer is going on till friday, $1.99/mo.
              </h5>
              <h1 class="display-3 fw-bold mb-3">Word’s No. 1 app for Online traning.</h1>
              <p class="pe-lg-10 mb-5">
                Use your data to access your favorite content from our growing roster of
                premier publishers.
              </p>
              <a href="#" class="btn btn-primary rounded-pill p-3"
                >Download - It’s free</a
              >
              <a
                href="https://www.youtube.com/watch?v=JRzWRZahOVU"
                class="popup-youtube fs-4 text-inherit ms-3"
                ><img
                  src="https://geeksui.codescandy.com/geeks/assets/images/svg/play-btn.svg"
                  alt="play"
                  class="me-2"
                />Watch Demo</a
              >
            </div>
          </div>
          <div class="col-lg-6 d-flex justify-content-center">
            <div class="position-relative">
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/bg-thumb.svg"
                alt="img"
                class=" "
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/girl-image.png"
                alt="girl"
                class="w-100 w-md-auto position-absolute end-0 bottom-0"
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/frame-1.svg"
                alt="frame"
                class="position-absolute top-0 ms-lg-n10 ms-n19"
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/frame-2.svg"
                alt="frame"
                class="position-absolute bottom-0 start-0 ms-lg-n14 ms-n6 mb-n7"
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/target.svg"
                alt="target"
                class="position-absolute bottom-0 mb-10 ms-n10 ms-lg-n1"
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/sound.svg"
                alt="sound"
                class="position-absolute top-0 start-0 mt-18 ms-lg-n19 ms-n8"
              />
              <img
                src="https://geeksui.codescandy.com/geeks/assets/images/background/acedamy-img/trophy.svg"
                alt="trophy"
                class="position-absolute top-0 start-0 ms-lg-n14 ms-n5"
              />
            </div>
          </div>
        </div>
      </div>

      <div class="shape shape-bottom">
        <svg
          width="3000"
          height="500"
          viewBox="0 0 3000 500"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path d="M0 500H3000V0L0 500Z" fill="#fff"></path>
        </svg>
      </div>

    </section>
  </div>

  <section class="py-5" id="features">
    <div class="container">
      <div class="text-center mb-5">
        <h2>Our Application Features.</h2>
      </div>
      <div class="row">
        <div class="col-md-4 mb-7 feature-box p-5">
          <div class="text-center px-lg-3">
            <span class="svg-icon svg-icon-lg mb-3">
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M15.6 5.59998L20.9 10.9C21.3 11.3 21.3 11.9 20.9 12.3L17.6 15.6L11.6 9.59998L15.6 5.59998ZM2.3 12.3L7.59999 17.6L11.6 13.6L5.59999 7.59998L2.3 10.9C1.9 11.3 1.9 11.9 2.3 12.3Z"
                  fill="#6425fe"
                ></path>
                <path
                  opacity="0.3"
                  d="M17.6 15.6L12.3 20.9C11.9 21.3 11.3 21.3 10.9 20.9L7.59998 17.6L13.6 11.6L17.6 15.6ZM10.9 2.3L5.59998 7.6L9.59998 11.6L15.6 5.6L12.3 2.3C11.9 1.9 11.3 1.9 10.9 2.3Z"
                  fill="#6425fe"
                ></path>
              </svg>
            </span>
            <h3>Industry-leading designs</h3>
            <p>Achieve virtually any design and layout from within the one template.</p>
          </div>
        </div>
        <div class="col-md-4 mb-7 feature-box p-5">
          <div class="text-center px-lg-3">
            <span class="svg-icon svg-icon-lg text-primary mb-3">
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  opacity="0.3"
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M4.85714 1H11.7364C12.0911 1 12.4343 1.12568 12.7051 1.35474L17.4687 5.38394C17.8057 5.66895 18 6.08788 18 6.5292V19.0833C18 20.8739 17.9796 21 16.1429 21H4.85714C3.02045 21 3 20.8739 3 19.0833V2.91667C3 1.12612 3.02045 1 4.85714 1ZM7 13C7 12.4477 7.44772 12 8 12H15C15.5523 12 16 12.4477 16 13C16 13.5523 15.5523 14 15 14H8C7.44772 14 7 13.5523 7 13ZM8 16C7.44772 16 7 16.4477 7 17C7 17.5523 7.44772 18 8 18H11C11.5523 18 12 17.5523 12 17C12 16.4477 11.5523 16 11 16H8Z"
                  fill="#6425fe"
                ></path>
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M6.85714 3H14.7364C15.0911 3 15.4343 3.12568 15.7051 3.35474L20.4687 7.38394C20.8057 7.66895 21 8.08788 21 8.5292V21.0833C21 22.8739 20.9796 23 19.1429 23H6.85714C5.02045 23 5 22.8739 5 21.0833V4.91667C5 3.12612 5.02045 3 6.85714 3ZM7 13C7 12.4477 7.44772 12 8 12H15C15.5523 12 16 12.4477 16 13C16 13.5523 15.5523 14 15 14H8C7.44772 14 7 13.5523 7 13ZM8 16C7.44772 16 7 16.4477 7 17C7 17.5523 7.44772 18 8 18H11C11.5523 18 12 17.5523 12 17C12 16.4477 11.5523 16 11 16H8Z"
                  fill="#6425fe"
                ></path>
              </svg>
            </span>
            <h3>Learn from the docs</h3>
            <p>
              Whether you're a startup or a global enterprise, learn how to integrate with
              Front.
            </p>
          </div>
        </div>
        <div class="col-md-4 mb-7 feature-box p-5">
          <div class="text-center px-lg-3">
            <span class="svg-icon svg-icon-lg text-primary mb-3">
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M15 19.5229C15 20.265 15.9624 20.5564 16.374 19.9389L22.2227 11.166C22.5549 10.6676 22.1976 10 21.5986 10H17V4.47708C17 3.73503 16.0376 3.44363 15.626 4.06106L9.77735 12.834C9.44507 13.3324 9.80237 14 10.4014 14H15V19.5229Z"
                  fill="#6425fe"
                ></path>
                <path
                  opacity="0.3"
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M3 6.5C3 5.67157 3.67157 5 4.5 5H9.5C10.3284 5 11 5.67157 11 6.5C11 7.32843 10.3284 8 9.5 8H4.5C3.67157 8 3 7.32843 3 6.5ZM3 18.5C3 17.6716 3.67157 17 4.5 17H9.5C10.3284 17 11 17.6716 11 18.5C11 19.3284 10.3284 20 9.5 20H4.5C3.67157 20 3 19.3284 3 18.5ZM2.5 11C1.67157 11 1 11.6716 1 12.5C1 13.3284 1.67157 14 2.5 14H6.5C7.32843 14 8 13.3284 8 12.5C8 11.6716 7.32843 11 6.5 11H2.5Z"
                  fill="#6425fe"
                ></path>
              </svg>
            </span>
            <h3>Accelerate your business</h3>
            <p>We help power millions of businesses to built and run smoothly.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-light rounded-2 mx-3 mx-lg-10 py-5">
    <div class="container content-space-2 content-space-lg-3">
      <div class="row">
        <div class="col-lg-7 mb-9 mb-lg-0">
          <div class="pe-lg-6">
            <!-- Browser Device -->
            <figure class="device-browser">
              <div class="device-browser-header">
                <div class="device-browser-header-btn-list">
                  <span class="device-browser-header-btn-list-btn"></span>
                  <span class="device-browser-header-btn-list-btn"></span>
                  <span class="device-browser-header-btn-list-btn"></span>
                </div>
                <div class="device-browser-header-browser-bar">
                  www.finding.lk
                </div>
              </div>

              <div class="device-browser-frame">
                <img
                  class="device-browser-img"
                  src="https://htmlstream.com/preview/front-v4.3.1/assets/img/1618x1010/img6.jpg"
                  alt="Image Description"
                />
              </div>
            </figure>
            <!-- End Browser Device -->
          </div>
        </div>
        <!-- End Col -->

        <div class="col-lg-5 p-5">
          <!-- Heading -->
          <div class="mb-4">
            <h1>
              Grow your business <br />
              by using our apps
            </h1>
            <p>
              We help businesses bring ideas to life in the digital world, by designing
              and implementing the technology tools that they need to win.
            </p>
          </div>
          <!-- End Heading -->

          <!-- List Checked -->
          <ul class="list-checked list-checked-primary mb-5">
            <li class="list-checked-item">Less routine – more creativity</li>
            <li class="list-checked-item">Hundreds of thousands saved</li>
            <li class="list-checked-item">Scale budgets efficiently</li>
          </ul>
          <!-- End List Checked -->

          <a class="btn btn-primary" href="#">Get started</a>

          <!-- End Row -->
        </div>
        <!-- End Col -->
      </div>
      <!-- End Row -->
    </div>
  </section>

  <section class="container py-5 why-choose-us" id="whyus">
    <div class="row row-grid align-items-center">
      <div class="col-lg-4">
        <div class="py-lg-5 text-lg-left">
          <h3 class="mb-3">Why you choose Our app?</h3>
          <p class="lead lh-180">
            Build responsive, mobile-first projects on the web with the world's most
            popular front-end component library.
          </p>
          <a href="#" class="btn btn-primary btn-icon rounded-pill mt-4">
            <span class="btn-inner--text">Learn more</span>
            <span class="btn-inner--icon">
              <i class="fas fa-angle-right"></i>
            </span>
          </a>
        </div>
      </div>
      <div class="col-lg-7 ml-lg-auto">
        <div class="row">
          <div class="col-md-6">
            <div class="card hover-shadow-lg">
              <div class="px-4 py-5">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  width="151px"
                  height="107px"
                  viewBox="0 0 151 107"
                  version="1.1"
                  class="injected-svg svg-inject"
                  style="height: 64px; width: auto"
                >
                  <!-- Generator: Sketch 51.2 (57519) - http://www.bohemiancoding.com/sketch -->
                  <title>Save_to_Cloud</title>
                  <desc>Created with Sketch.</desc>
                  <defs></defs>
                  <g
                    id="Page-1"
                    stroke="none"
                    stroke-width="1"
                    fill="none"
                    fill-rule="evenodd"
                  >
                    <g id="Save_to_Cloud" transform="translate(1.000000, 1.000000)">
                      <path
                        d="M147.9,64.8 C147.9,78.6 136.4,89.8 122.3,89.8 L105.5,90.1 L103.9,90.1 L65.7,90.8 L56.9,91 L27.8,91.3 C15.3,91.3 6.9,82.7 5.1,71.3 C4.8,69.7 4.7,68.1 4.7,66.5 C4.7,52.5 15.2,40.5 30.4,41.3 C34.5,27.9 50.5,22.2 63.4,28.5 C69.5,15.4 84.9,5.3 100.6,5.3 C116,5.3 128.8,14.2 134.7,26.9 C136.2,30.1 137.3,33.6 137.9,37.3 C138.2,39.3 138.4,41.3 138.4,43.3 C138.4,43.7 138.4,43.4 138.4,43.4 C138.4,43.4 138.4,43.5 138.4,43.6 C141,45.6 143.1,48.4 144.8,51.5 C146.8,55.6 147.9,60.3 147.9,64.8 Z"
                        id="Shape"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M145.1,56.4 C145.1,70.2 133.6,81.4 119.5,81.4 L102.7,81.7 L101.1,81.7 L62.9,82.4 L54.1,82.6 L25,82.9 C15.8,82.9 8.9,78.3 5.1,71.2 C4.8,69.6 4.7,68 4.7,66.4 C4.7,52.4 15.2,40.4 30.4,41.2 C34.5,27.8 50.5,22.1 63.4,28.4 C69.5,15.3 84.9,5.2 100.6,5.2 C116,5.2 128.8,14.1 134.7,26.8 C135.2,29.4 135.5,32.1 135.5,34.9 C135.5,35.3 135.5,35 135.5,35 C135.5,35 135.5,35.1 135.5,35.2 C136.3,35.8 137.1,36.5 137.8,37.3 C141.3,41 143.7,46.2 144.7,51.5 C145,53.2 145.1,54.8 145.1,56.4 Z"
                        id="Shape"
                        class="fill-primary-300"
                        fill-rule="nonzero"
                      ></path>
                      <polygon
                        id="Shape"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                        points="108.6 60.9 108.6 89.8 62.8 90.7 62.8 47.1 94.8 47.1"
                      ></polygon>
                      <path
                        d="M47.2,91 L48.4,91"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M75,8.3 C69.4,12.3 64.8,17.8 61.9,24.2 C58.7,22.6 55.1,21.7 51.2,21.7 C40.4,21.7 30.8,28.8 27.9,38.7 C27.4,38.7 28.4,38.7 27.9,38.7 C13.3,38.7 0.5,50.5 0.5,65 C0.5,79.6 12.3,91.4 26.9,91.4 L39.4,91.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M80.2,5.1 C80.1,5.2 80,5.2 79.8,5.3"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M109.2,89.9 L121.5,89.7 C136.1,89.7 147.9,77.9 147.9,63.3 C147.9,54.9 144,47.5 137.9,42.7 C137.9,42.1 138,41.4 138,40.8 C138,18.8 120.1,0.9 98.1,0.9 C95.1,0.9 92.1,1.2 89.3,1.9"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <polygon
                        id="Shape"
                        class="fill-primary-100"
                        fill-rule="nonzero"
                        points="103 58.7 103 103.7 57.3 103.7 57.3 44.9 89.2 44.9"
                      ></polygon>
                      <polyline
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        points="85.6 44.9 89.2 44.9 103 58.7 103 103.7 57.3 103.7 57.3 44.9 78.1 44.9"
                      ></polyline>
                      <path
                        d="M68.7,79.6 L91.1,79.6"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M68.7,71.2 L91.1,71.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M68.7,88.2 L78.3,88.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <polyline
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        points="89.4 52.5 89.4 59.7 102 59.7"
                      ></polyline>
                      <path
                        d="M27.9,38.7 C32.1,39 36.7,40.7 40.1,42.7"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M61.9,24.2 C63.9,25 65.9,26.4 67.4,27.7"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                    </g>
                  </g>
                </svg>
              </div>
              <div class="px-4 pb-5">
                <h5>Cloud compute</h5>
                <p class="text-muted">
                  Some quick example text to build on the card title and make up the bulk
                  of the card's content.
                </p>
              </div>
            </div>
            <div class="card hover-shadow-lg">
              <div class="px-4 py-5">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  width="147px"
                  height="124px"
                  viewBox="0 0 147 124"
                  version="1.1"
                  class="injected-svg svg-inject"
                  style="height: 64px; width: auto"
                >
                  <!-- Generator: Sketch 51.2 (57519) - http://www.bohemiancoding.com/sketch -->
                  <title>Database</title>
                  <desc>Created with Sketch.</desc>
                  <defs></defs>
                  <g
                    id="Page-1"
                    stroke="none"
                    stroke-width="1"
                    fill="none"
                    fill-rule="evenodd"
                  >
                    <g id="Database" transform="translate(1.000000, 2.000000)">
                      <path
                        d="M104.5,98.6 C126.4,98 143.8,90.8 143.8,82.1 C143.8,77.5 143.8,69.5 143.8,61.4 C143.8,61.4 143.8,61.4 143.8,61.4 C143.8,53.4 143.8,45.4 143.8,40.8 C143.8,32 126.5,24.9 104.5,24.3 C104.5,31.7 104.5,91.5 104.5,98.6 Z"
                        id="Shape"
                        class="fill-primary-200"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M0.8,53.1 L0.8,21.9 C0.8,10 23.3,0.4 51,0.4 C78.7,0.4 101.2,10 101.2,21.9 L101.2,99.1 C101.2,111 78.7,120.6 51,120.6 C30.7,120.6 13.3,115.5 5.3,108.1 C2.4,105.4 0.7,102.3 0.7,99.1 L0.7,68.2"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M101.3,26.4 L101.3,99.1 C101.3,111 78.8,120.6 51.1,120.6 C30.8,120.6 13.4,115.5 5.4,108.1 L5.4,26.5 C5.4,15.2 26.9,6 53.4,6 C79.8,5.9 101.3,15.1 101.3,26.4 Z"
                        id="Shape"
                        class="fill-primary-300"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M101.3,26.4 L101.3,27.4 C93.2,36.8 74.1,43.5 51.8,43.5 C32,43.5 14.8,38.3 5.5,30.6 L5.5,26.5 C5.5,15.2 27,6 53.5,6 C79.8,5.9 101.3,15.1 101.3,26.4 Z"
                        id="Shape"
                        class="fill-primary-100"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M93.8,10.6 C98.6,13.9 101.3,17.8 101.3,21.9 C101.3,33.8 78.8,43.4 51.1,43.4 C36.5,43.4 23.3,40.7 14.1,36.5"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M84.8,6 C84.9,6 85.1,6.1 85.2,6.1"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M0.8,21.6 C1.1,9.8 23.5,0.3 51,0.3 C61.5,0.3 71.2,1.7 79.2,4"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M7.5,32.7 C6.5,31.9 5.6,31.2 4.8,30.4"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M101.3,72.1 C101.3,84 78.8,93.6 51.1,93.6 C23.4,93.6 0.9,84 0.9,72.1"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M44.5,68.4 C19.9,67 0.9,58 0.9,47.1"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M85.9,62.5 C78.1,65.7 67.9,67.9 56.6,68.4"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M101.3,47 C101.3,51.1 98.6,54.9 94,58.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M35.6,119.5 C40.5,120.2 45.7,120.5 51.1,120.5 C78.8,120.5 101.3,110.9 101.3,99 C101.3,88.1 101.3,43.6 101.3,26.3 C101.3,24.5 101.3,22.9 101.3,21.8"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M18.9,115.6 C20,116 21.1,116.4 22.3,116.7"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M0.8,66.9 L0.8,99 C0.8,102.2 2.4,105.3 5.4,108 C7.4,109.9 10,111.6 13.2,113.1"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M0.8,21.9 L0.8,46.4"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M140.1,30.4 C142.5,32.6 143.8,35.1 143.8,37.7 C143.8,46.9 127.1,54.5 105.9,55.1"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M134.8,26.7 C135.2,26.9 135.6,27.1 136,27.3"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M106,20.3 C114.9,20.6 123,22.1 129.4,24.4"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M106,76.8 C127.1,76.2 143.8,68.6 143.9,59.4 C143.9,59.4 143.9,59.4 143.9,59.4"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M143.8,38 C143.8,37.9 143.8,37.8 143.8,37.7"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M106,98.6 C127.1,98 143.9,90.4 143.9,81.2 C143.9,76.3 143.9,67.9 143.9,59.4 C143.9,59.4 143.9,59.4 143.9,59.4 C143.9,57.6 143.9,55.8 143.9,54 L143.9,50.1"
                        id="Shape"
                        class="stroke-primary-400"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <ellipse
                        id="Oval"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                        transform="translate(23.217540, 52.517080) rotate(-75.977653) translate(-23.217540, -52.517080) "
                        cx="23.21754"
                        cy="52.51708"
                        rx="3.59999519"
                        ry="6.29999159"
                      ></ellipse>
                      <ellipse
                        id="Oval"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                        transform="translate(23.197560, 77.633410) rotate(-75.977653) translate(-23.197560, -77.633410) "
                        cx="23.19756"
                        cy="77.63341"
                        rx="3.59999519"
                        ry="6.29999159"
                      ></ellipse>
                      <ellipse
                        id="Oval"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                        transform="translate(23.182140, 104.545380) rotate(-75.977653) translate(-23.182140, -104.545380) "
                        cx="23.18214"
                        cy="104.54538"
                        rx="3.59999519"
                        ry="6.29999159"
                      ></ellipse>
                    </g>
                  </g>
                </svg>
              </div>
              <div class="px-4 pb-5">
                <h5>Dedicated servers</h5>
                <p class="text-muted">
                  Some quick example text to build on the card title and make up the bulk
                  of the card's content.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-6 pt-lg-6 pt-4">
            <div class="card hover-shadow-lg">
              <div class="px-4 py-5">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  width="150px"
                  height="103px"
                  viewBox="0 0 150 103"
                  version="1.1"
                  class="injected-svg svg-inject"
                  style="height: 64px; width: auto"
                >
                  <!-- Generator: Sketch 51.2 (57519) - http://www.bohemiancoding.com/sketch -->
                  <title>Folder_2</title>
                  <desc>Created with Sketch.</desc>
                  <defs></defs>
                  <g
                    id="Page-1"
                    stroke="none"
                    stroke-width="1"
                    fill="none"
                    fill-rule="evenodd"
                  >
                    <g id="Folder_2" transform="translate(2.000000, 1.000000)">
                      <path
                        d="M124.5,82.8 L18.2,82.8 C14,82.8 10.7,79.4 10.7,75.3 L10.7,8.2 C10.7,4 14.1,0.7 18.2,0.7 L124.4,0.7 C128.6,0.7 131.9,4.1 131.9,8.2 L131.9,75.3 C132,79.4 128.6,82.8 124.5,82.8 Z"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M124.8,82.8 L22,82.8 C18.1,82.8 14.9,79.6 14.9,75.7 L14.9,13.3 C14.9,9.4 18.1,6.2 22,6.2 L124.8,6.2 C128.7,6.2 131.9,9.4 131.9,13.3 L131.9,75.7 C132,79.6 128.8,82.8 124.8,82.8 Z"
                        id="Shape"
                        class="fill-primary-500"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M10.7,25.7 L10.7,8.2 C10.7,4 14.1,0.7 18.2,0.7 L45.5,0.7"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M132,43.1 L132,75.2 C132,79.4 128.6,82.7 124.5,82.7 L18.2,82.7 C14,82.7 10.7,79.3 10.7,75.2 L10.7,40.3"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M63.5,0.6 L124.4,0.6 C128.6,0.6 131.9,4 131.9,8.1 L131.9,34.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M53.6,0.6 L53.9,0.6"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M137,16.3 L93.5,16.3 C89.3,16.3 85.2,17.8 81.9,20.4 L70.5,29.7 C67.2,32.4 63.1,33.8 58.9,33.8 L9.4,33.8 C3.9,33.8 -0.4,38.7 0.5,44.2 L9.5,92.5 C10.2,97 14.1,100.4 18.6,100.4 L124.1,100.4 C128.6,100.4 132.5,97.1 133.2,92.7 L145.9,26.8 C146.8,21.3 142.6,16.3 137,16.3 Z"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M140.1,60.4 L145.9,31.3 C146.8,26.1 142.6,21.4 137.2,21.4 L94.8,21.4 C90.7,21.4 86.7,22.8 83.5,25.3 L72.4,34.1 C69.2,36.6 65.2,38 61.1,38 L12.8,38 C7.4,38 3.3,42.6 4.1,47.7 L12.9,93 C13.6,97.2 17.3,100.4 21.8,100.4 L124.7,100.4 C129.1,100.4 132.9,97.3 133.6,93.1 L140.1,60.4"
                        id="Shape"
                        class="fill-primary-200"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M135.1,82.8 L135.4,81.4"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M139.4,60.5 L145.9,26.7 C146.8,21.2 142.6,16.2 137,16.2 L93.5,16.2 C89.3,16.2 85.2,17.7 81.9,20.3 L70.5,29.6 C67.2,32.3 63.1,33.7 58.9,33.7 L9.4,33.7 C3.9,33.7 -0.4,38.6 0.5,44.1 L9.5,92.4 C10.2,96.9 14.1,100.3 18.6,100.3 L124.1,100.3 C128.6,100.3 132.5,97 133.2,92.6 L133.7,89.9"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                    </g>
                  </g>
                </svg>
              </div>
              <div class="px-4 pb-5">
                <h5>Block storage</h5>
                <p class="text-muted">
                  Some quick example text to build on the card title and make up the bulk
                  of the card's content.
                </p>
              </div>
            </div>
            <div class="card hover-shadow-lg">
              <div class="px-4 py-5">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  width="151px"
                  height="102px"
                  viewBox="0 0 151 102"
                  version="1.1"
                  class="injected-svg svg-inject"
                  style="height: 64px; width: auto"
                >
                  <!-- Generator: Sketch 51.2 (57519) - http://www.bohemiancoding.com/sketch -->
                  <title>Laptop</title>
                  <desc>Created with Sketch.</desc>
                  <defs></defs>
                  <g
                    id="Page-1"
                    stroke="none"
                    stroke-width="1"
                    fill="none"
                    fill-rule="evenodd"
                  >
                    <g id="Laptop" transform="translate(2.000000, 1.000000)">
                      <path
                        d="M147.2,89.2 L147.2,93 C147.2,96.5 144.2,99.3 140.6,99.3 L6.8,99.3 C3.1,99.3 0.2,96.5 0.2,93 L0.2,89.2 L60.7,89.2 C61.2,90.6 62.6,91.6 64.3,91.6 L83.2,91.6 C84.9,91.6 86.3,90.6 86.8,89.2 L147.2,89.2 Z"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M139.7,89.2 L7.7,89.2 L7.7,6.3 C7.7,3.3 10.1,0.8 13.2,0.8 L134.2,0.8 C137.2,0.8 139.7,3.2 139.7,6.3 L139.7,89.2 Z"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M139.7,89.2 L11,89.2 L11,7 C11,5.1 12.6,3.5 14.5,3.5 L134.4,3.5 C137.3,3.5 139.7,5.9 139.7,8.8 L139.7,89.2 Z"
                        id="Shape"
                        class="fill-primary-100"
                        fill-rule="nonzero"
                      ></path>
                      <polyline
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        points="56.2 89.2 7.7 89.2 7.7 46.2"
                      ></polyline>
                      <path
                        d="M7.7,25.6 L7.7,6.2 C7.7,3.2 10.1,0.7 13.2,0.7 L134.2,0.7 C137.2,0.7 139.7,3.1 139.7,6.2 L139.7,89.1 L104.7,89.1"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M7.7,34.6 L7.7,34"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M147.2,92.2 L147.2,94.9 C147.2,97.4 144.3,99.4 140.7,99.4 L10.3,99.4 C6.7,99.4 3.8,97.4 3.8,94.9 L3.8,92.2 L59.2,92.2 C59.7,93.2 61.1,93.9 62.7,93.9 L84.7,93.9 C86.3,93.9 87.7,93.2 88.2,92.2 L147.2,92.2 Z"
                        id="Shape"
                        class="fill-primary-300"
                        fill-rule="nonzero"
                      ></path>
                      <path
                        d="M13.9,7.7 L133.1,7.7"
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                      ></path>
                      <polyline
                        id="Shape"
                        class="fill-neutral"
                        fill-rule="nonzero"
                        points="106.8 89.5 13.9 89.5 13.9 7.7 133.1 7.7 133.1 89.5 120.6 89.5"
                      ></polyline>
                      <polyline
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        points="53.4 89.2 13.9 89.2 13.9 7.7 133.1 7.7 133.1 26.6"
                      ></polyline>
                      <path
                        d="M97.3,89.2 L96.6,89.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M133.1,89.2 L102.1,89.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M133.1,35.4 L133.1,89.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                      <path
                        d="M133,89.2 L147.2,89.2 L147.2,93 C147.2,96.5 144.2,99.3 140.6,99.3 L6.8,99.3 C3.1,99.3 0.2,96.5 0.2,93 L0.2,89.2 L60.7,89.2 C61.2,90.6 62.6,91.6 64.3,91.6 L83.2,91.6 C84.4,91.6 85.4,91.1 86.1,90.2"
                        id="Shape"
                        class="stroke-primary"
                        stroke-width="3"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      ></path>
                    </g>
                  </g>
                </svg>
              </div>
              <div class="px-4 pb-5">
                <h5>Dedicated cloud</h5>
                <p class="text-muted">
                  Some quick example text to build on the card title and make up the bulk
                  of the card's content.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="py-5 bg-light" id="price">
    <div class="container">
      <div class="mb-5 text-center">
        <h1 class="mt-4">No hidden charges. Pick your plan.</h1>
        <div class="fluid-paragraph mt-3">
          <p class="lead lh-180">
            We'll make sure we build everything you need from now on
          </p>
        </div>
      </div>
      <div class="pricing-container">
        <div class="text-center mb-5">
          <div class="btn-group" role="group">
            <button type="button" class="btn btn-secondary active" data-pricing="monthly">
              Monthly billing
            </button>
            <button type="button" class="btn btn-secondary" data-pricing="yearly">
              Yearly billing
            </button>
          </div>
        </div>
        <div class="pricing card-group flex-column flex-lg-row mb-3">
          <div class="card card-pricing text-center px-3 mb-5 mb-lg-0 mx-2">
            <span class="h6 w-60 mx-auto px-4 py-1 rounded-bottom bg-theme text-white"
              >Starter</span
            >
            <div class="card-header py-5 border-0">
              <div class="h1 text-theme text-center mb-0" data-pricing-value="12">
                $<span class="price">3</span><span class="h6 ml-2">/ per month</span>
              </div>
            </div>
            <div class="card-body delimiter-top">
              <ul class="list-unstyled mb-4">
                <li>Up to 5 users</li>
                <li>Basic support on Github</li>
                <li>Monthly updates</li>
                <li>Free cancelation</li>
              </ul>
              <button type="button" class="btn btn-sm btn-neutral px-3 py-2">
                Order now
              </button>
            </div>
          </div>
          <div
            class="card card-pricing popular scale-110 text-center px-3 mb-5 mb-lg-0 mx-2"
          >
            <span class="h6 w-60 mx-auto px-4 py-1 rounded-bottom bg-theme text-white"
              >Professional</span
            >
            <div class="card-header py-5 border-0">
              <div class="h1 text-theme text-center mb-0" data-pricing-value="24">
                $<span class="price">6</span><span class="h6 ml-2">/ per month</span>
              </div>
            </div>
            <div class="card-body delimiter-top">
              <ul class="list-unstyled mb-4">
                <li>Up to 5 users</li>
                <li>Basic support on Github</li>
                <li>Monthly updates</li>
                <li>Free cancelation</li>
              </ul>
              <button type="button" class="btn btn-sm btn-neutral px-3 py-2">
                Order now
              </button>
            </div>
          </div>
          <div class="card card-pricing text-center px-3 mb-5 mb-lg-0 mx-2">
            <span class="h6 w-60 mx-auto px-4 py-1 rounded-bottom bg-theme text-white"
              >Business</span
            >
            <div class="card-header py-5 border-0">
              <div class="h1 text-theme text-center mb-0" data-pricing-value="36">
                $<span class="price">9</span><span class="h6 ml-2">/ per month</span>
              </div>
            </div>
            <div class="card-body delimiter-top">
              <ul class="list-unstyled mb-4">
                <li>Up to 5 users</li>
                <li>Basic support on Github</li>
                <li>Monthly updates</li>
                <li>Free cancelation</li>
              </ul>
              <button type="button" class="btn btn-sm btn-neutral px-3 py-2">
                Order now
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="py-5" id="feedback">
    <div class="container">
      <div class="mb-5 text-center">
        <h1 class="mt-4">What our customers say</h1>
        <div class="fluid-paragraph mt-3">
          <p class="lead lh-180">
            Always looking for better ways to do things, innovate and help people achieve
            their goals.
          </p>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-11">
          <div class="swiper-js-container row align-items-center">
            <div class="col-xl-4 d-none d-xl-block">
              <div class="pr-4">
                <h5>Testimonials</h5>
                <p class="lead mt-3">
                  Don't trust us. See what our clients are saying about our product.
                </p>
              </div>
            </div>
            <div class="col-xl-8">
              <Slider />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <footer class="pt-lg-10 pt-5 footer bg-white border-top">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-6 col-12">
          <!-- about company -->
          <div class="mb-4">
            <img
              src="https://don.finding.lk/images/rentalize_logo.png"
              alt=""
              class="logo-inverse"
              width="130"
            />
            <div class="mt-4">
              <p>
                Geek is feature-rich components and beautifully Bootstrap UIKit for
                developers, built with bootstrap responsive framework.
              </p>
              <!-- social media -->
              <div class="fs-4 mt-4">
                <a href="#" class="mdi mdi-facebook fs-4 text-muted me-2"></a>
                <a href="#" class="mdi mdi-twitter text-muted me-2"></a>
                <a href="#" class="mdi mdi-instagram text-muted"></a>
              </div>
            </div>
          </div>
        </div>
        <div class="offset-lg-1 col-lg-2 col-md-3 col-6">
          <div class="mb-4">
            <!-- list -->
            <h5 class="fw-bold mb-3">Company</h5>
            <ul class="list-unstyled nav nav-footer flex-column nav-x-0">
              <li><a href="#" class="nav-link">About</a></li>
              <li><a href="#" class="nav-link">Pricing</a></li>
              <li><a href="#" class="nav-link">Blog</a></li>
              <li><a href="#" class="nav-link">Careers</a></li>
              <li><a href="#" class="nav-link">Contact</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-2 col-md-3 col-6">
          <div class="mb-4">
            <!-- list -->
            <h5 class="fw-bold mb-3">Support</h5>
            <ul class="list-unstyled nav nav-footer flex-column nav-x-0">
              <li><a href="#" class="nav-link">Help and Support</a></li>
              <li><a href="#" class="nav-link">Become Instructor</a></li>
              <li><a href="#" class="nav-link">Get the app</a></li>
              <li><a href="#" class="nav-link">FAQ’s</a></li>
              <li><a href="#" class="nav-link">Tutorial</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-3 col-md-12">
          <!-- contact info -->
          <div class="mb-4">
            <h5 class="fw-bold mb-3">Get in touch</h5>
            <p>339 McDermott Points Hettingerhaven, NV 15283</p>
            <p class="mb-1">Email: <a href="#">support@geeksui.com</a></p>
            <p>Phone: <span class="text-dark fw-semibold">(000) 123 456 789</span></p>
            <div class="d-flex">
              <a href="#"
                ><img
                  src="https://geeksui.codescandy.com/geeks/assets/images/svg/appstore.svg"
                  alt=""
                  class="img-fluid"
              /></a>
              <a href="#" class="ms-2"
                ><img
                  src="https://geeksui.codescandy.com/geeks/assets/images/svg/playstore.svg"
                  alt=""
                  class="img-fluid"
              /></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
import "bootstrap/dist/css/bootstrap.min.css";
import Slider from "./components/Slider.vue";
</script>

<style scoped>
:root {
  --theme-color: #6425fe;
}

.footer,
.nav-footer .nav-link {
  color: #475569;
}

.nav-x-0 .nav-link {
  padding-left: 0 !important;
  padding-right: 0 !important;
}
.nav-footer .nav-link {
  font-size: 0.875rem;
  line-height: 1.5rem;
  padding: 0.2rem 1rem;
}

header .nav-link {
 color: #6425fe;
}

.btn-primary {
  background: #6425fe;
}

.svg-icon {
  display: block;
  margin-top: 0.125rem;
}

.svg-icon-lg > svg {
  width: 4.25rem;
  height: 4.25rem;
}

.device-browser {
  position: relative;
  z-index: 1;
  display: block;
  max-width: 100%;
  width: 50rem;
  height: auto;
  margin-left: auto;
  margin-right: auto;
}

.device-browser-frame {
  background: #fff;
  box-shadow: 0 2.75rem 5.5rem -3.5rem rgba(189, 197, 209, 0.5),
    0 2rem 4rem -2rem rgba(33, 50, 91, 0.3);
  border-bottom-right-radius: 0.5rem;
  border-bottom-left-radius: 0.5rem;
}

.device-browser-img {
  max-width: 100%;
  height: auto;
  border-bottom-right-radius: 0.5rem;
  border-bottom-left-radius: 0.5rem;
}

.device-browser-header {
  position: relative;
  display: flex;
  max-width: 50rem;
  background: #fff;
  border-bottom: 0.0625rem solid #f1f3f8;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
  padding: 0.5rem 6.5rem;
}

.device-browser-header-btn-list {
  display: flex;
  grid-gap: 0.25rem;
  position: absolute;
  top: calc(50% - 0.25rem);
  left: 1rem;
}

.device-browser-header-btn-list-btn {
  width: 0.5rem;
  height: 0.5rem;
  background-color: #e7eaf3;
  border-radius: 50%;
}

.device-browser-header-browser-bar {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  color: #677788;
  background-color: #e7eaf3;
  font-size: 0.5rem;
  border-radius: 0.125rem;
}

.device-browser-lg {
  width: 60rem;
}

.device-browser-lg .device-browser-header {
  max-width: 60rem;
}

.shape-bottom {
  bottom: 0;
  left: 0;
  right: 0;
}
.shape {
  position: absolute;
  z-index: 1;
}

.hero {
  /* background: #f8f9fa; */
  background: rgba(246,240,253,1);
  /* background: linear-gradient(50deg, #fff 0, #6425fe 100%) !important; */
}

.bg-theme {
  background: #6425fe;
}

.text-theme {
  color: #6425fe;
}

.shape-bottom > svg {
  width: 100%;
  height: auto;
  margin-bottom: -1px;
  transform-origin: top center;
}

.content-space-t-lg-4 {
  padding-top: 10rem !important;
}

.zi-1 {
  z-index: 1 !important;
}

.zi-2 {
  z-index: 2 !important;
}

.feature-box {
  cursor: pointer;
}

.feature-box:hover {
  background-color: #ffff;
  box-shadow: 0px 25px 60px 0px rgba(12.999999999999986, 32.00000000000001, 96, 0.08);
}

.card-pricing .card-header {
  padding: 1rem 1.5rem;
  margin-bottom: 0;
  background-color: transparent;
}

.pricing .card-body {
  flex: 1 1 auto;
  min-height: 1px;
  padding: 1.5rem;
  color: #8492a6;
}
.pricing .card-group .card {
  margin-bottom: 15px;
}
.pricing .card {
  position: relative;
  margin-bottom: 30px;
  box-shadow: 0 0.75rem 1.5rem rgba(18, 38, 63, 0.03);
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 1px solid #eff2f7;
  border-radius: 0.375rem;
}

.card-pricing .card-header {
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}

.card-pricing .list-unstyled li {
  padding: 0.5rem 0;
}

@media (max-width: 991.98px) {
  .card-pricing.scale-110 {
    transform: scale(1) !important;
  }
}

.btn-neutral {
  background-color: #fff;
  color: #273444;
  border: 1px solid #eff2f7;
}
.btn-neutral:hover {
  border-color: #e5eaf2;
  background-color: #f7f7f7;
}
.btn-neutral:not(:disabled):not(.disabled).active {
  border-color: #6e00ff;
  color: #6e00ff;
  background-color: #fff;
}

.stroke-primary {
  stroke: #6425fe !important;
}

.fill-primary-300 {
  fill: #c599ff !important;
}
.fill-primary-100 {
  fill: white !important;
}
.fill-primary-200 {
  fill: #e2ccff !important;
}

.fill-primary-500 {
  fill: #8b33ff !important;
}

.why-choose-us .card {
  position: relative;
  margin-bottom: 30px;
  box-shadow: 0 0.75rem 1.5rem rgba(18, 38, 63, 0.03);
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.7;
  border: 1px solid #eff2f7;
  border-radius: 0.375rem;
}

.hover-shadow-lg:hover {
  box-shadow: 0 1rem 3rem rgba(31, 45, 61, 0.125) !important;
}
</style>
