# css-danco
unit 8 Bootstrap
=================

http://getbootstrap.com/

Базовый шаблон
----------------
Начните с базового HTML шаблона. 

Приведеный ниже HTML-код использует минимизированную версию Bootstrap.
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap 101 Template</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <h1>Привет, мир!</h1>

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
```

Grid
=====


      <!DOCTYPE html>
      <html lang="en">
        <head>
          <meta charset="utf-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1">
          <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
          <meta name="description" content="">
          <meta name="author" content="">
          <link rel="icon" href="../images/favicon.ico">

          <title>Grid Template for Bootstrap</title>

          <!-- Bootstrap core CSS -->
          <link href="../css/bootstrap.min.css" rel="stylesheet">

          <!-- Custom styles for this template -->
          <link href="grid.css" rel="stylesheet">

          
          <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
          <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
            <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
          <![endif]-->
        </head>

        <body>
          <div class="container">

            <div class="page-header">
              <h1>Bootstrap grid examples</h1>
              <p class="lead">Basic grid layouts to get you familiar with building within the Bootstrap grid system.</p>
            </div>

            <h3>Three equal columns</h3>
            <p>Get three equal-width columns <strong>starting at desktops and scaling to large desktops</strong>. On mobile devices, tablets and below, the columns will automatically stack.</p>
            <div class="row">
              <div class="col-md-4">.col-md-4</div>
              <div class="col-md-4">.col-md-4</div>
              <div class="col-md-4">.col-md-4</div>
            </div>

            <h3>Three unequal columns</h3>
            <p>Get three columns <strong>starting at desktops and scaling to large desktops</strong> of various widths. Remember, grid columns should add up to twelve for a single horizontal block. More than that, and columns start stacking no matter the viewport.</p>
            <div class="row">
              <div class="col-md-3">.col-md-3</div>
              <div class="col-md-6">.col-md-6</div>
              <div class="col-md-3">.col-md-3</div>
            </div>

            <h3>Two columns</h3>
            <p>Get two columns <strong>starting at desktops and scaling to large desktops</strong>.</p>
            <div class="row">
              <div class="col-md-8">.col-md-8</div>
              <div class="col-md-4">.col-md-4</div>
            </div>

            <h3>Full width, single column</h3>
            <p class="text-warning">No grid classes are necessary for full-width elements.</p>

            <hr>

            <h3>Two columns with two nested columns</h3>
            <p>Per the documentation, nesting is easy—just put a row of columns within an existing column. This gives you two columns <strong>starting at desktops and scaling to large desktops</strong>, with another two (equal widths) within the larger column.</p>
            <p>At mobile device sizes, tablets and down, these columns and their nested columns will stack.</p>
            <div class="row">
              <div class="col-md-8">
                .col-md-8
                <div class="row">
                  <div class="col-md-6">.col-md-6</div>
                  <div class="col-md-6">.col-md-6</div>
                </div>
              </div>
              <div class="col-md-4">.col-md-4</div>
            </div>

            <hr>

            <h3>Mixed: mobile and desktop</h3>
            <p>The Bootstrap 3 grid system has four tiers of classes: xs (phones), sm (tablets), md (desktops), and lg (larger desktops). You can use nearly any combination of these classes to create more dynamic and flexible layouts.</p>
            <p>Each tier of classes scales up, meaning if you plan on setting the same widths for xs and sm, you only need to specify xs.</p>
            <div class="row">
              <div class="col-xs-12 col-md-8">.col-xs-12 .col-md-8</div>
              <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
            </div>
            <div class="row">
              <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
              <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
              <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
            </div>
            <div class="row">
              <div class="col-xs-6">.col-xs-6</div>
              <div class="col-xs-6">.col-xs-6</div>
            </div>

            <hr>

            <h3>Mixed: mobile, tablet, and desktop</h3>
            <p></p>
            <div class="row">
              <div class="col-xs-12 col-sm-6 col-lg-8">.col-xs-12 .col-sm-6 .col-lg-8</div>
              <div class="col-xs-6 col-lg-4">.col-xs-6 .col-lg-4</div>
            </div>
            <div class="row">
              <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
              <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
              <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
            </div>

            <hr>

            <h3>Column clearing</h3>
            <p><a href="http://getbootstrap.com/css/#grid-responsive-resets">Clear floats</a> at specific breakpoints to prevent awkward wrapping with uneven content.</p>
            <div class="row">
              <div class="col-xs-6 col-sm-3">
                .col-xs-6 .col-sm-3
                <br>
                Resize your viewport or check it out on your phone for an example.
              </div>
              <div class="col-xs-6 col-sm-3">.col-xs-6 .col-sm-3</div>

              <!-- Add the extra clearfix for only the required viewport -->
              <div class="clearfix visible-xs"></div>

              <div class="col-xs-6 col-sm-3">.col-xs-6 .col-sm-3</div>
              <div class="col-xs-6 col-sm-3">.col-xs-6 .col-sm-3</div>
            </div>

            <hr>

            <h3>Offset, push, and pull resets</h3>
            <p>Reset offsets, pushes, and pulls at specific breakpoints.</p>
            <div class="row">
              <div class="col-sm-5 col-md-6">.col-sm-5 .col-md-6</div>
              <div class="col-sm-5 col-sm-offset-2 col-md-6 col-md-offset-0">.col-sm-5 .col-sm-offset-2 .col-md-6 .col-md-offset-0</div>
            </div>
            <div class="row">
              <div class="col-sm-6 col-md-5 col-lg-6">.col-sm-6 .col-md-5 .col-lg-6</div>
              <div class="col-sm-6 col-md-5 col-md-offset-2 col-lg-6 col-lg-offset-0">.col-sm-6 .col-md-5 .col-md-offset-2 .col-lg-6 .col-lg-offset-0</div>
            </div>

          </div> <!-- /container -->
          
        </body>
      </html>


css
----

      h4 {
        margin-top: 25px;
      }
      .row {
        margin-bottom: 20px;
      }
      .row .row {
        margin-top: 10px;
        margin-bottom: 0;
      }
      [class*="col-"] {
        padding-top: 15px;
        padding-bottom: 15px;
        background-color: #eee;
        background-color: rgba(86,61,124,.15);
        border: 1px solid #ddd;
        border: 1px solid rgba(86,61,124,.2);
      }

      hr {
        margin-top: 40px;
        margin-bottom: 40px;
      }


cover
======

      <!DOCTYPE html>
      <html lang="en">
        <head>
          <meta charset="utf-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1">
          <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
          <meta name="description" content="">
          <meta name="author" content="">
          <link rel="icon" href="../images/favicon.ico">

          <title>Cover Template for Bootstrap</title>

          <!-- Bootstrap core CSS -->
          <link href="../css/bootstrap.min.css" rel="stylesheet">

          <!-- Custom styles for this template -->
          <link href="cover.css" rel="stylesheet">

          
          <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
          <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
            <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
          <![endif]-->
        </head>

        <body>

          <div class="site-wrapper">

            <div class="site-wrapper-inner">

              <div class="cover-container">

                <div class="masthead clearfix">
                  <div class="inner">
                    <h3 class="masthead-brand">Cover</h3>
                    <nav>
                      <ul class="nav masthead-nav">
                        <li class="active"><a href="#">Home</a></li>
                        <li><a href="#">Features</a></li>
                        <li><a href="#">Contact</a></li>
                      </ul>
                    </nav>
                  </div>
                </div>

                <div class="inner cover">
                  <h1 class="cover-heading">Cover your page.</h1>
                  <p class="lead">Cover is a one-page template for building simple and beautiful home pages. Download, edit the text, and add your own fullscreen background photo to make it your own.</p>
                  <p class="lead">
                    <a href="#" class="btn btn-lg btn-default">Learn more</a>
                  </p>
                </div>

                <div class="mastfoot">
                  <div class="inner">
                    <p>Cover template for <a href="http://getbootstrap.com">Bootstrap</a>, by <a href="https://twitter.com/mdo">@mdo</a>.</p>
                  </div>
                </div>

              </div>

            </div>

          </div>

          <!-- Bootstrap core JavaScript
          ================================================== -->
          <!-- Placed at the end of the document so the pages load faster -->
          <script src="../js/jquery.min.js"></script>
          <script src="../js/bootstrap.min.js"></script>
          
        </body>
      </html>

         /*
         * Globals
         */

        /* Links */
        a,
        a:focus,
        a:hover {
          color: #fff;
        }

        /* Custom default button */
        .btn-default,
        .btn-default:hover,
        .btn-default:focus {
          color: #333;
          text-shadow: none; /* Prevent inheritence from `body` */
          background-color: #fff;
          border: 1px solid #fff;
        }


        /*
         * Base structure
         */

        html,
        body {
          height: 100%;
          background-color: #333;
        }
        body {
          color: #fff;
          text-align: center;
          text-shadow: 0 1px 3px rgba(0,0,0,.5);
        }

        /* Extra markup and styles for table-esque vertical and horizontal centering */
        .site-wrapper {
          display: table;
          width: 100%;
          height: 100%; /* For at least Firefox */
          min-height: 100%;
          -webkit-box-shadow: inset 0 0 100px rgba(0,0,0,.5);
                  box-shadow: inset 0 0 100px rgba(0,0,0,.5);
        }
        .site-wrapper-inner {
          display: table-cell;
          vertical-align: top;
        }
        .cover-container {
          margin-right: auto;
          margin-left: auto;
        }

        /* Padding for spacing */
        .inner {
          padding: 30px;
        }


        /*
         * Header
         */
        .masthead-brand {
          margin-top: 10px;
          margin-bottom: 10px;
        }

        .masthead-nav > li {
          display: inline-block;
        }
        .masthead-nav > li + li {
          margin-left: 20px;
        }
        .masthead-nav > li > a {
          padding-right: 0;
          padding-left: 0;
          font-size: 16px;
          font-weight: bold;
          color: #fff; /* IE8 proofing */
          color: rgba(255,255,255,.75);
          border-bottom: 2px solid transparent;
        }
        .masthead-nav > li > a:hover,
        .masthead-nav > li > a:focus {
          background-color: transparent;
          border-bottom-color: #a9a9a9;
          border-bottom-color: rgba(255,255,255,.25);
        }
        .masthead-nav > .active > a,
        .masthead-nav > .active > a:hover,
        .masthead-nav > .active > a:focus {
          color: #fff;
          border-bottom-color: #fff;
        }

        @media (min-width: 768px) {
          .masthead-brand {
            float: left;
          }
          .masthead-nav {
            float: right;
          }
        }


        /*
         * Cover
         */

        .cover {
          padding: 0 20px;
        }
        .cover .btn-lg {
          padding: 10px 20px;
          font-weight: bold;
        }


        /*
         * Footer
         */

        .mastfoot {
          color: #999; /* IE8 proofing */
          color: rgba(255,255,255,.5);
        }


        /*
         * Affix and center
         */

        @media (min-width: 768px) {
          /* Pull out the header and footer */
          .masthead {
            position: fixed;
            top: 0;
          }
          .mastfoot {
            position: fixed;
            bottom: 0;
          }
          /* Start the vertical centering */
          .site-wrapper-inner {
            vertical-align: middle;
          }
          /* Handle the widths */
          .masthead,
          .mastfoot,
          .cover-container {
            width: 100%; /* Must be percentage or pixels for horizontal alignment */
          }
        }

        @media (min-width: 992px) {
          .masthead,
          .mastfoot,
          .cover-container {
            width: 700px;
          }
        }






navbar-fixed
============


        <!DOCTYPE html>
        <html lang="en">
          <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
            <meta name="description" content="">
            <meta name="author" content="">
            <link rel="icon" href="../images/favicon.ico">

            <title>Fixed Top Navbar Example for Bootstrap</title>

            <!-- Bootstrap core CSS -->
            <link href="../css/bootstrap.min.css" rel="stylesheet">

            
            <!-- Custom styles for this template -->
            <link href="navbar-fixed-top.css" rel="stylesheet">

            
            <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
            <!--[if lt IE 9]>
              <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
              <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
            <![endif]-->
          </head>

          <body>

            <!-- Fixed navbar -->
            <nav class="navbar navbar-default navbar-fixed-top">
              <div class="container">
                <div class="navbar-header">
                  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                  </button>
                  <a class="navbar-brand" href="#">Project name</a>
                </div>
                <div id="navbar" class="navbar-collapse collapse">
                  <ul class="nav navbar-nav">
                    <li class="active"><a href="#">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li class="dropdown">
                      <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                      <ul class="dropdown-menu">
                        <li><a href="#">Action</a></li>
                        <li><a href="#">Another action</a></li>
                        <li><a href="#">Something else here</a></li>
                        <li role="separator" class="divider"></li>
                        <li class="dropdown-header">Nav header</li>
                        <li><a href="#">Separated link</a></li>
                        <li><a href="#">One more separated link</a></li>
                      </ul>
                    </li>
                  </ul>
                  <ul class="nav navbar-nav navbar-right">
                    <li><a href="../navbar/">Default</a></li>
                    <li><a href="../navbar-static-top/">Static top</a></li>
                    <li class="active"><a href="./">Fixed top <span class="sr-only">(current)</span></a></li>
                  </ul>
                </div><!--/.nav-collapse -->
              </div>
            </nav>

            <div class="container">

              <!-- Main component for a primary marketing message or call to action -->
              <div class="jumbotron">
                <h1>Navbar example</h1>
                <p>This example is a quick exercise to illustrate how the default, static and fixed to top navbar work. It includes the responsive CSS and HTML, so it also adapts to your viewport and device.</p>
                <p>To see the difference between static and fixed top navbars, just scroll.</p>
                <p>
                  <a class="btn btn-lg btn-primary" href="#navbar" role="button">View navbar docs &raquo;</a>
                </p>
              </div>

            </div> <!-- /container -->


            <!-- Bootstrap core JavaScript
            ================================================== -->
            <!-- Placed at the end of the document so the pages load faster -->
            <script src="../js/jquery.min.js"></script>
            
            <script src="../js/bootstrap.min.js"></script>
            
          </body>
        </html>



        body {
          min-height: 2000px;
          padding-top: 70px;
        }




sticky-footer-navbar
====================

        <!DOCTYPE html>
        <html lang="en">
          <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
            <meta name="description" content="">
            <meta name="author" content="">
            <link rel="icon" href="../images/favicon.ico">

            <title>Sticky Footer Navbar Template for Bootstrap</title>

            <!-- Bootstrap core CSS -->
            <link href="../css/bootstrap.min.css" rel="stylesheet">

            <!-- Custom styles for this template -->
            <link href="sticky-footer-navbar.css" rel="stylesheet">

            
            <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
            <!--[if lt IE 9]>
              <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
              <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
            <![endif]-->
          </head>

          <body>

            <!-- Fixed navbar -->
            <nav class="navbar navbar-default navbar-fixed-top">
              <div class="container">
                <div class="navbar-header">
                  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                  </button>
                  <a class="navbar-brand" href="#">Project name</a>
                </div>
                <div id="navbar" class="collapse navbar-collapse">
                  <ul class="nav navbar-nav">
                    <li class="active"><a href="#">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li class="dropdown">
                      <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                      <ul class="dropdown-menu">
                        <li><a href="#">Action</a></li>
                        <li><a href="#">Another action</a></li>
                        <li><a href="#">Something else here</a></li>
                        <li role="separator" class="divider"></li>
                        <li class="dropdown-header">Nav header</li>
                        <li><a href="#">Separated link</a></li>
                        <li><a href="#">One more separated link</a></li>
                      </ul>
                    </li>
                  </ul>
                </div><!--/.nav-collapse -->
              </div>
            </nav>

            <!-- Begin page content -->
            <div class="container">
              <div class="page-header">
                <h1>Sticky footer with fixed navbar</h1>
              </div>
              <p class="lead">Pin a fixed-height footer to the bottom of the viewport in desktop browsers with this custom HTML and CSS. A fixed navbar has been added with <code>padding-top: 60px;</code> on the <code>body > .container</code>.</p>
              <p>Back to <a href="../sticky-footer">the default sticky footer</a> minus the navbar.</p>
            </div>

            <footer class="footer">
              <div class="container">
                <p class="text-muted">Place sticky footer content here.</p>
              </div>
            </footer>


            <!-- Bootstrap core JavaScript
            ================================================== -->
            <!-- Placed at the end of the document so the pages load faster -->
            <script src="../js/jquery.min.js"></script>
            
            <script src="../js/bootstrap.min.js"></script>
            
          </body>
        </html>



          /* Sticky footer styles
          -------------------------------------------------- */
          html {
            position: relative;
            min-height: 100%;
          }
          body {
            /* Margin bottom by footer height */
            margin-bottom: 60px;
          }
          .footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            /* Set the fixed height of the footer here */
            height: 60px;
            background-color: #f5f5f5;
          }


          /* Custom page CSS
          -------------------------------------------------- */
          /* Not required for template or sticky footer method. */

          body > .container {
            padding: 60px 15px 0;
          }
          .container .text-muted {
            margin: 20px 0;
          }

          .footer > .container {
            padding-right: 15px;
            padding-left: 15px;
          }

          code {
            font-size: 80%;
          }


carousel
========

        <!DOCTYPE html>
        <html lang="en">
          <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
            <meta name="description" content="">
            <meta name="author" content="">
            <link rel="icon" href="../images/favicon.ico">

            <title>Carousel Template for Bootstrap</title>

            <!-- Bootstrap core CSS -->
            <link href="../css/bootstrap.min.css" rel="stylesheet">

            
             <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
            <!--[if lt IE 9]>
              <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
              <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
            <![endif]-->

            <!-- Custom styles for this template -->
            <link href="carousel.css" rel="stylesheet">
          </head>
        <!-- NAVBAR
        ================================================== -->
          <body>
            <div class="navbar-wrapper">
              <div class="container">

                <nav class="navbar navbar-inverse navbar-static-top">
                  <div class="container">
                    <div class="navbar-header">
                      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                      </button>
                      <a class="navbar-brand" href="#">Project name</a>
                    </div>
                    <div id="navbar" class="navbar-collapse collapse">
                      <ul class="nav navbar-nav">
                        <li class="active"><a href="#">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#contact">Contact</a></li>
                        <li class="dropdown">
                          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                          <ul class="dropdown-menu">
                            <li><a href="#">Action</a></li>
                            <li><a href="#">Another action</a></li>
                            <li><a href="#">Something else here</a></li>
                            <li role="separator" class="divider"></li>
                            <li class="dropdown-header">Nav header</li>
                            <li><a href="#">Separated link</a></li>
                            <li><a href="#">One more separated link</a></li>
                          </ul>
                        </li>
                      </ul>
                    </div>
                  </div>
                </nav>

              </div>
            </div>


            <!-- Carousel
            ================================================== -->
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
              <!-- Indicators -->
              <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
              </ol>
              <div class="carousel-inner" role="listbox">
                <div class="item active">
                  <img class="first-slide" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="First slide">
                  <div class="container">
                    <div class="carousel-caption">
                      <h1>Example headline.</h1>
                      <p>Note: If you're viewing this page via a <code>file://</code> URL, the "next" and "previous" Glyphicon buttons on the left and right might not load/display properly due to web browser security rules.</p>
                      <p><a class="btn btn-lg btn-primary" href="#" role="button">Sign up today</a></p>
                    </div>
                  </div>
                </div>
                <div class="item">
                  <img class="second-slide" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Second slide">
                  <div class="container">
                    <div class="carousel-caption">
                      <h1>Another example headline.</h1>
                      <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                      <p><a class="btn btn-lg btn-primary" href="#" role="button">Learn more</a></p>
                    </div>
                  </div>
                </div>
                <div class="item">
                  <img class="third-slide" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Third slide">
                  <div class="container">
                    <div class="carousel-caption">
                      <h1>One more for good measure.</h1>
                      <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                      <p><a class="btn btn-lg btn-primary" href="#" role="button">Browse gallery</a></p>
                    </div>
                  </div>
                </div>
              </div>
              <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div><!-- /.carousel -->


            <!-- Marketing messaging and featurettes
            ================================================== -->
            <!-- Wrap the rest of the page in another container to center all the content. -->

            <div class="container marketing">

              <!-- Three columns of text below the carousel -->
              <div class="row">
                <div class="col-lg-4">
                  <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" width="140" height="140">
                  <h2>Heading</h2>
                  <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.</p>
                  <p><a class="btn btn-default" href="#" role="button">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
                <div class="col-lg-4">
                  <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" width="140" height="140">
                  <h2>Heading</h2>
                  <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                  <p><a class="btn btn-default" href="#" role="button">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
                <div class="col-lg-4">
                  <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" width="140" height="140">
                  <h2>Heading</h2>
                  <p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
                  <p><a class="btn btn-default" href="#" role="button">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
              </div><!-- /.row -->


              <!-- START THE FEATURETTES -->

              <hr class="featurette-divider">

              <div class="row featurette">
                <div class="col-md-7">
                  <h2 class="featurette-heading">First featurette heading. <span class="text-muted">It'll blow your mind.</span></h2>
                  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5">
                  <img class="featurette-image img-responsive center-block" data-src="holder.js/500x500/auto" alt="Generic placeholder image">
                </div>
              </div>

              <hr class="featurette-divider">

              <div class="row featurette">
                <div class="col-md-7 col-md-push-5">
                  <h2 class="featurette-heading">Oh yeah, it's that good. <span class="text-muted">See for yourself.</span></h2>
                  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5 col-md-pull-7">
                  <img class="featurette-image img-responsive center-block" data-src="holder.js/500x500/auto" alt="Generic placeholder image">
                </div>
              </div>

              <hr class="featurette-divider">

              <div class="row featurette">
                <div class="col-md-7">
                  <h2 class="featurette-heading">And lastly, this one. <span class="text-muted">Checkmate.</span></h2>
                  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5">
                  <img class="featurette-image img-responsive center-block" data-src="holder.js/500x500/auto" alt="Generic placeholder image">
                </div>
              </div>

              <hr class="featurette-divider">

              <!-- /END THE FEATURETTES -->


              <!-- FOOTER -->
              <footer>
                <p class="pull-right"><a href="#">Back to top</a></p>
                <p>&copy; 2015 Company, Inc. &middot; <a href="#">Privacy</a> &middot; <a href="#">Terms</a></p>
              </footer>

            </div><!-- /.container -->


            <!-- Bootstrap core JavaScript
            ================================================== -->
            <!-- Placed at the end of the document so the pages load faster -->
            <script src="../js/jquery.min.js"></script>
            <script src="../js/bootstrap.min.js"></script>
            
          </body>
        </html>


        /* GLOBAL STYLES
        -------------------------------------------------- */
        /* Padding below the footer and lighter body text */

        body {
          padding-bottom: 40px;
          color: #5a5a5a;
        }


        /* CUSTOMIZE THE NAVBAR
        -------------------------------------------------- */

        /* Special class on .container surrounding .navbar, used for positioning it into place. */
        .navbar-wrapper {
          position: absolute;
          top: 0;
          right: 0;
          left: 0;
          z-index: 20;
        }

        /* Flip around the padding for proper display in narrow viewports */
        .navbar-wrapper > .container {
          padding-right: 0;
          padding-left: 0;
        }
        .navbar-wrapper .navbar {
          padding-right: 15px;
          padding-left: 15px;
        }
        .navbar-wrapper .navbar .container {
          width: auto;
        }


        /* CUSTOMIZE THE CAROUSEL
        -------------------------------------------------- */

        /* Carousel base class */
        .carousel {
          height: 500px;
          margin-bottom: 60px;
        }
        /* Since positioning the image, we need to help out the caption */
        .carousel-caption {
          z-index: 10;
        }

        /* Declare heights because of positioning of img element */
        .carousel .item {
          height: 500px;
          background-color: #777;
        }
        .carousel-inner > .item > img {
          position: absolute;
          top: 0;
          left: 0;
          min-width: 100%;
          height: 500px;
        }


        /* MARKETING CONTENT
        -------------------------------------------------- */

        /* Center align the text within the three columns below the carousel */
        .marketing .col-lg-4 {
          margin-bottom: 20px;
          text-align: center;
        }
        .marketing h2 {
          font-weight: normal;
        }
        .marketing .col-lg-4 p {
          margin-right: 10px;
          margin-left: 10px;
        }


        /* Featurettes
        ------------------------- */

        .featurette-divider {
          margin: 80px 0; /* Space out the Bootstrap <hr> more */
        }

        /* Thin out the marketing headings */
        .featurette-heading {
          font-weight: 300;
          line-height: 1;
          letter-spacing: -1px;
        }


        /* RESPONSIVE CSS
        -------------------------------------------------- */

        @media (min-width: 768px) {
          /* Navbar positioning foo */
          .navbar-wrapper {
            margin-top: 20px;
          }
          .navbar-wrapper .container {
            padding-right: 15px;
            padding-left: 15px;
          }
          .navbar-wrapper .navbar {
            padding-right: 0;
            padding-left: 0;
          }

          /* The navbar becomes detached from the top, so we round the corners */
          .navbar-wrapper .navbar {
            border-radius: 4px;
          }

          /* Bump up size of carousel content */
          .carousel-caption p {
            margin-bottom: 20px;
            font-size: 21px;
            line-height: 1.4;
          }

          .featurette-heading {
            font-size: 50px;
          }
        }

        @media (min-width: 992px) {
          .featurette-heading {
            margin-top: 120px;
          }
        }
