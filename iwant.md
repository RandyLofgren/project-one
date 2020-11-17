<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.1/css/bulma.min.css">
    <link rel="stylesheet" href="./assets/style.css">
    <title>Trail Weather Tracker </title>
</head>

<body>
    <section class="hero is-info">
        <div class="hero-body">
            <div class="container">
                <h1 class="title">
                    Welcome to The Tail Weather Tracker!
                </h1>
                <h2 class="subtitle">
                    Search for The weather of your favorite hiking trails. Select a State or zipcode and the dates you
                    want to
                    view the weather for. Happy Hiking!
                </h2>
            </div>
        </div>
    </section>
   

    <div class="tile is-ancestor">
        <div class="tile is-parent">
            <article class="tile is-child box">
                <div class="field is-6">
                    <div class="control has-icons-left has-icons-right">
                        <input class="input" type="text" placeholder="City">
                        <span class="icon is-left">
                            <i class="fas fa-globe"></i>
                        </span>
    
                    </div>
                </div>
    
                <div class="field is-6">
                    <div class="control has-icons-left has-icons-right">
                        <input class="input" type="text" placeholder="State">
                        <span class="icon is-left">
                            <i class="fas fa-globe"></i>
                        </span>
    
                    </div>
                </div>
    
                <div class="control">
                    <button class="button is-primary">Submit</button>
                </div>
            </article>
        </div>
        <div class="tile is-parent is-verticle is-8">
            <article class="tile is-child box">
                <article class="tile is-child notification is-danger">
                    <p class="title">Wide tile</p>
                    <p class="subtitle">Aligned with the right tile</p>
                    <div class="content">
                        <!-- Content -->
                    </div>
                </article>
            </article>
        </div>
    </div>

    <div class="tile is-ancestor">
        <div class="tile is-parent">
          <article class="tile is-child box">
            <p class="title">Side column</p>
            <p class="subtitle">With some content</p>
            <div class="content">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.</p>
            </div>
          </article>
        </div>
        <div class="tile is-parent is-8">
          <article class="tile is-child box">
            <p class="title">Main column</p>
            <p class="subtitle">With some content</p>
            <div class="content">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.</p>
            </div>
          </article>
        </div>
      </div>

    <button id="testBtn">TESTING</button>















    <script defer src="https://use.fontawesome.com/releases/v5.14.0/js/all.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"
        integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
    <script src="./assets/script.js"></script>
</body>

</html>