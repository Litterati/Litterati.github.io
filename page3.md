---
permalink: /chatbot.html
layout: none
---
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Hugo 0.104.2">
    <title>Album example · Bootstrap v5.2</title>

    <link rel="canonical" href="https://getbootstrap.com/docs/5.2/examples/album/">

    

    

<link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }

      .b-example-divider {
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

      .b-example-vr {
        flex-shrink: 0;
        width: 1.5rem;
        height: 100vh;
      }

      .bi {
        vertical-align: -.125em;
        fill: currentColor;
      }

      .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
      }

      .nav-scroller .nav {
        display: flex;
        flex-wrap: nowrap;
        padding-bottom: 1rem;
        margin-top: -1px;
        overflow-x: auto;
        text-align: center;
        white-space: nowrap;
        -webkit-overflow-scrolling: touch;
      }
    </style>

    
  </head>
  <body>
    
{% include header.html %}
<main>

  <section class="py-5 text-center container">
    <div class="row py-lg-5">
      <div class="col-lg-6 col-md-8 mx-auto">
        <h1 class="fw-light">Add your Event Or Pictures Using The Bot</h1>
        <p class="lead text-muted">Just Answer The Questions That Come Up On The Page</p>
        <p>
          <a href="#" class="btn btn-primary my-2">Main call to action</a>
          <a href="#" class="btn btn-secondary my-2">Secondary action</a>
        </p>
      </div>
    </div>
  </section>
<section style="background-color: #eee;">
  <div class="container py-5">

    <div class="row d-flex justify-content-center">
      <div class="col-md-10 col-lg-8 col-xl-6">

        <div class="card" id="chat2">
          <div class="card-header d-flex justify-content-between align-items-center p-3">
            <h5 class="mb-0">Chat</h5>
            <button type="button" class="btn btn-primary btn-sm" data-mdb-ripple-color="dark">Let's Chat
              App</button>
          </div>
          <div class="card-body" data-mdb-perfect-scrollbar="true" style="position: relative; height: 400px">

            <div class="d-flex flex-row justify-content-start">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava3-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
              <div>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">Hi</p>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">How are you ...???
                </p>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">What are you doing
                  tomorrow? Can we come up a bar?</p>
                <p class="small ms-3 mb-3 rounded-3 text-muted">23:58</p>
              </div>
            </div>

            <div class="divider d-flex align-items-center mb-4">
              <p class="text-center mx-3 mb-0" style="color: #a2aab7;">Today</p>
            </div>

            <div class="d-flex flex-row justify-content-end mb-4 pt-1">
              <div>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">Hiii, I'm good.</p>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">How are you doing?</p>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">Long time no see! Tomorrow
                  office. will
                  be free on sunday.</p>
                <p class="small me-3 mb-3 rounded-3 text-muted d-flex justify-content-end">00:06</p>
              </div>
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava4-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
            </div>

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava3-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
              <div>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">Okay</p>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">We will go on
                  Sunday?</p>
                <p class="small ms-3 mb-3 rounded-3 text-muted">00:07</p>
              </div>
            </div>

            <div class="d-flex flex-row justify-content-end mb-4">
              <div>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">That's awesome!</p>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">I will meet you Sandon Square
                  sharp at
                  10 AM</p>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">Is that okay?</p>
                <p class="small me-3 mb-3 rounded-3 text-muted d-flex justify-content-end">00:09</p>
              </div>
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava4-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
            </div>

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava3-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
              <div>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">Okay i will meet
                  you on
                  Sandon Square</p>
                <p class="small ms-3 mb-3 rounded-3 text-muted">00:11</p>
              </div>
            </div>

            <div class="d-flex flex-row justify-content-end mb-4">
              <div>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">Do you have pictures of Matley
                  Marriage?</p>
                <p class="small me-3 mb-3 rounded-3 text-muted d-flex justify-content-end">00:11</p>
              </div>
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava4-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
            </div>

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava3-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
              <div>
                <p class="small p-2 ms-3 mb-1 rounded-3" style="background-color: #f5f6f7;">Sorry I don't
                  have. i
                  changed my phone.</p>
                <p class="small ms-3 mb-3 rounded-3 text-muted">00:13</p>
              </div>
            </div>

            <div class="d-flex flex-row justify-content-end">
              <div>
                <p class="small p-2 me-3 mb-1 text-white rounded-3 bg-primary">Okay then see you on sunday!!
                </p>
                <p class="small me-3 mb-3 rounded-3 text-muted d-flex justify-content-end">00:15</p>
              </div>
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava4-bg.webp"
                alt="avatar 1" style="width: 45px; height: 100%;">
            </div>

          </div>
          <div class="card-footer text-muted d-flex justify-content-start align-items-center p-3">
            <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava3-bg.webp"
              alt="avatar 3" style="width: 40px; height: 100%;">
            <input type="text" class="form-control form-control-lg" id="exampleFormControlInput1"
              placeholder="Type message">
            <a class="ms-1 text-muted" href="#!"><i class="fas fa-paperclip"></i></a>
            <a class="ms-3 text-muted" href="#!"><i class="fas fa-smile"></i></a>
            <a class="ms-3" href="#!"><i class="fas fa-paper-plane"></i></a>
          </div>
        </div>

      </div>
    </div>

  </div>
</section>
</main>

<footer class="text-muted py-5">
  <div class="container">
    <p class="float-end mb-1">
      <a href="#">Back to top</a>
    </p>
    <p class="mb-1">Album example is &copy; Bootstrap, but please download and customize it for yourself!</p>
    <p class="mb-0">New to Bootstrap? <a href="/">Visit the homepage</a> or read our <a href="../getting-started/introduction/">getting started guide</a>.</p>
  </div>
</footer>


    <script src="../assets/dist/js/bootstrap.bundle.min.js"></script>

      
  </body>
</html>
