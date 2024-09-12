---
layout: splash
title: "Die Wiener Akademische Philharmonie"
excerpt: "Die Wiener Akademische Philharmonie"
header: 
  image: /assets/images/stage3_long.jpeg
url: "/"



---

<style>
  pre {
    white-space: pre-wrap; 
  }
  .body{
    padding-left: 0px;
  }
  .container {
    display: flex;
    flex-wrap: wrap;
}
.roboto-slab-font {
  font-family: "Roboto Slab", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  color: black;
}
.column {
    flex: 1;
    padding: 20px; /* Fixed padding width */
    font-size: clamp(1em, 2vw, 1.2em); /* Example font size with a maximum of 1.5em */
    box-sizing: border-box;
    font-family:"Roboto Slab";
    min-width: 300px;
}
.column img {
    display:block;
    margin-left: auto;
    margin-right: auto;
    max-width: 100%;
    min-width: 300px;
    height: auto; /* To maintain aspect ratio of the image */
    /*display: block; /* Ensures the image behaves as a block element */
}
.container-main-image{
    display: flex;
    justify-content: center;
    align-items: center;
}
.container2 {
    display: flex;
    flex-wrap: wrap;
    padding-top: 10px;
    padding-bottom: 10px;
}
.column2 {
    flex: 1;
    float: right;
    text-align: right;
    padding: 20px; /* Fixed padding width */
    font-size: clamp(2em, 4vw, 2.2em); /* Example font size with a maximum of 1.5em */
    color: maroon;
    box-sizing: border-box;
    font-family:"Roboto Slab";
    min-width: 300px;
}
.column3 {
    flex: 1;
    padding: 20px; /* Fixed padding width */
    font-size: clamp(1em, 2vw, 1.2em); /* Example font size with a maximum of 1.5em */
    box-sizing: border-box;
    font-family:"Roboto Slab";
    min-width: 300px; 
}
.split {
    flex: 1;
    text-align:left;
    padding: 10px; /* Fixed padding width */
    font-size: clamp(2em, 4vw, 2.2em); /* Example font size with a maximum of 1.5em */
    color: maroon;
    box-sizing: border-box;
    font-family:"Roboto Slab";
    font-size: 4em;
}
.split-main {
    flex: 1;
    text-align:left;
    padding: 0px;
    padding-left: 0px; /* Fixed padding width */
    font-size: clamp(2em, 4vw, 2.2em); /* Example font size with a maximum of 1.5em */
    color: maroon;
    box-sizing: border-box;
    font-family:"Roboto Slab";
    font-size: 4em;
}
.split2 {
    flex: 1;
    padding-left: 0px;
    text-align:left;
    font-size: clamp(2em, 4vw, 2.2em); /* Example font size with a maximum of 1.5em */
    color: black;
    box-sizing: border-box;
    font-family:"Roboto Slab";
    font-size: 1.2em;
}
.line {
    width: 2px;
    background-color: black;
}
@media (max-width: 400px) {
    .column img {
        float: left; /* Reset float for smaller screens */
        margin-left: 0; /* Reset margin */
        margin-bottom: 20px; /* Add margin below the image for better spacing */
        margin-top: 20px;
    }
    .column {
        flex: 100%;
        max-width: 100%;
        text-align: left; /* Reset text alignment */
    }
    .column2 {
      max-width: 100%;
    }
}
.concert {
    display: flex;
    margin-bottom: 20px;
    font-family: "Roboto Slab";
    justify-content: center;
}
.month {
    font-size: 24px;
    font-weight: bold;
    margin-right: 20px;
    flex:1 ;
    padding-right: 20px;
.details {
    font-size: 18px;
    flex:1 ; 
}

  </style>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Two Column Page</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100..900&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap" rel="stylesheet">

</head>
<body> 
    <div class = "container2">
      <div class="split-main">Herzlich Willkommen!</div>
    </div>
    <div class = "container2">
      <div class="split2" style = "font-size: 1.5em"> Wir freuen uns darauf, Sie bei unserem nächsten Konzert zu sehen. <br>
</div>
    </div>
    <div class="container">
        <div class="column">
        <br>
            <img src="../assets/images/mozartsall_waph_wave.jpg" alt="Image" width="550px">
        </div>
        <div class="column">
            <strong style="font-size: 1.4em;color: maroon">29.11.2024 / 19:30 <br>
            Wiener Konzerthaus / Mozartsaal <br>
            <a href="https://konzerthaus.at/concert/eventid/62252" style="text-decoration: none;">
                    <i class="fas fa-ticket-alt"></i> Karten
                </a></strong>
                <br>
                <br>
                <em>Christof Unterberger</em><br>
                >>Hommage á Puccini<<<br>
                <br>
                <em>Gioachino Rossini </em><br>
                >>Fagottkonzert<<<br>
                <br>
                <em>Felix Mendelssohn Bartholdy</em><br>
                >>4. Sinfonie in A-Dur op. 90, „Italienische“<<<br>
                <br>
                Fagott:
                <span style="font-weight: bold;">Benedikt Dinkhauser</span> <br>
                <br>
                Dirigent:
                <strong>Jon Svinghammar</strong>
        </div>
    </div>
    <div class = "container2">
      <div class="split">Vorschau</div>
    </div>
    <div class="container2">
        <div class="column2">
            <p>8 Juni 2025</p>
        </div>
        <div class="line"></div>
        <div class="column3">
            <br>
            <br>
            <p><strong>Wiener Musikverein</strong> </p>
            Am Pfingstsonntag werden wir die 2. Symphonie von Gustav Mahler, die “ Auferstehungssymphonie” unter der Leitung von Michal Juraszek aufführen.
        </div>
    </div>

    
</body>
</html>
<br>
<br>

