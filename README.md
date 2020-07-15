# Rio-Vista-YSA-Site
Rio Vista YSA Site - Dynamic site

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rio Vista YSA</title>


  <style>
    li {
      background-color: navy;
      display: inline;
      padding: 10px;
      list-style-type: empty;
    }

    .grid-container {
      display: grid;
    }

    html {
      font-family: sans-serif;
      background-color: white;
    }

    body {
      display: grid;
      width: 100%;
      max-width: 1200px;
      margin: 0 auto;
      background-color: white;
    }

    img {
      margin: 0 auto;
      max-width: 100%;
      padding: 10px;
      opacity: 0.75;
    }

    img:hover {
      opacity: 1.0;
    }
  </style>


</head>

<body>

  <!--To Do: Welcome Message + 2 Q's Pop-Up-->

  <img
    src="https://www.sltrib.com/resizer/A8ZqxBzReNruFLgHBkD38jnNWEQ=/1200x630/filters:quality(85)/arc-anglerfish-arc2-prod-sltrib.s3.amazonaws.com/public/IQ5L5APXVNGKTP6LUKVDPWGXWM.jpg"
    alt="The Church of Jesus Christ of Latter Day Saints Logo with Jesus Christ's Arms Extended">

  <ul>
    <li>About</li>
    <li>YSA</li>
    <li>Resources</li>
    <li>Join Us</li>
  </ul>

  <div class="grid-container">x

    <div class="grid-item-1">YSA<img
        src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80"
        alt="group of friends smiling" height="25%" width="25%"></div>

    <div class="grid-item-2">Leaders<img
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Men_in_colorful_suits_%28Unsplash%29.jpg/1200px-Men_in_colorful_suits_%28Unsplash%29.jpg"
        alt="some dashing and dapper men" height="25%" width="25%"></div>

    <div class="grid-item-3">Resources<img
        src="https://images.unsplash.com/photo-1554825959-e9a6670d4f18?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80"
        alt="resources for families and individuals" height="25%" width="25%"></div>

  </div>
  <!--
  <script>
    var person = prompt("Please enter your name", "Pepito Juarez");

    if (person == null || person == "") {
      txt = "User cancelled the prompt.";
    } else {
      txt = "Hello " + person + "! Enjoy your visit to our site.";
    }
  </script>
-->
</body>

</html>
