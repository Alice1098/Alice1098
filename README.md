<html>


<head>

    <title>Alice</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" media="screen and (min-width: 600px)" href="dmdd.css">
    <link rel="stylesheet" media="screen and (max-width: 600px)" href="mobile.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">

    <!-- Load an icon library to show a hamburger menu (bars) on small screens -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>


<body>

  <!-- Top Navigation Menu -->
<div class="topnav">
<a href="#home" class="active">Logo</a>
<!-- Navigation links (hidden by default) -->
<div id="myLinks">
  <a href="#news">First Page</a>
  <a href="#contact">Contact</a>
  <a href="#about">Links</a>
</div>
<!-- "Hamburger menu" / "Bar icon" to toggle the navigation links -->
<a href="javascript:void(0);" class="icon" onclick="myFunction()">
  <i class="fa fa-bars"></i>
</a>
</div>

    <!-- The next line will add an image to your page -->
    <img src="ice.jpeg" width= "150">


    <!-- Heading 1, your most important heading, starts here -->
    <h1>Alice</h1>
    <!-- Heading 1 finishes here -->

    <hr>

    <h2>About me</h2>

    <p> I am Alice, an 22 years old Italian student. I have been living in the U.K. for 3 years so far.
    </p>

    <p>I am a Birkbeck student. I am currently doing my second year. My Degree is a BA in Arts and media Management.
    </p>

    <p>I am working in an Art gallery in Windsor.
    </p>

    <h2>My favourite Web sites</h2>

    <!--edit the links and the URLs below for your favourite sites -->

    <div id="header">
    <ul>
        <li><a href="https://www.instagram.com">Instagram</a></li>
        <li><a href="https://www.artmonthly.co.uk">Artmonthly</a></li>
        <li><a href="https://www.tate.org.uk/visit/tate-modern">Tate Modern</a></li>
    </ul>
    </div>

  <script>/* Toggle between showing and hiding the navigation menu links when the user clicks on the hamburger menu / bar icon */
    function myFunction() {
      var x = document.getElementById("myLinks");
      if (x.style.display === "block") {
        x.style.display = "none";
      } else {
        x.style.display = "block";
      }
    }
</script>



</body>

