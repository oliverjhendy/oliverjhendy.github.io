---
layout: splash
header:
  image: /assets/images/stage3_long.jpeg
classes: wide
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
    padding: 20px; /* Fixed padding width */
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
    font-size: 1.5em;
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
      <div class="split-main">Herzlich Wilkommen!</div>
    </div>
    <div class = "container2">
      <div class="split2">
      Unser nächstes Konzert ist am 16. Juni 2024 im goldenen Saal des Musikvereins.
      Wir freuen uns auf ihren Besuch! 
      <br>
      <br>
      </div>
    </div>
    <div class="container">
        <div class="column">
            <img src="../assets/images/plakarte/240616-Rach.png" alt="Image" width="400px">
        </div>
        <div class="column">
            <strong>16.06.2024 / 19:30 </strong><br>
            Wiener Musikverein / Goldener Saal <br>
                <br>
                <em>Maurice Ravel</em><br>
                >>Konzert für Klavier und Orchester G-Dur<<<br>
                <br>
                <em>Igor Strawinsky</em><br>
                >>Suite aus dem Ballett „Der Feuervogel“; Fassung 1919<<<br>
                <br>
                <em>Sergej Wassilewitsch Rachmaninoff</em><br>
                >>Symphonie Nr. 2 e-Moll, op. 27<<<br>
                <br>
                Pianist:<br>
                <span style="font-weight: bold;">Maximilian Kromer</span> <br>
                <br>
                Dirigent:<br>
                <strong>Jon Svinghammar</strong><br>
                <br>
                <a href="https://www.musikverein.at/konzert/?id=00056a9d" target="_blank">
                  <strong>Tickets</strong>
                </a>
        </div>
    </div>
    <div class = "container2">
      <div class="split">Vorschau</div>
    </div>
    <div class="container2">
        <div class="column2">
            <p>31 August 2024</p>
        </div>
        <div class="line"></div>
        <div class="column3">
            <br>
            <br>
            <p><strong>Gars Open Air</strong> </p>
            Am 31.8. spielen wir anlässlich der EventBURG Beethovens 9. Symphonie mit einer hochkarätigen solistischen Besetzung unter der Leitung von Michal Juraszek
        </div>
    </div>
    <div class="container2">
        <div class="column2">
            <p>29 November 2024</p>
        </div>
        <div class="line"></div>
        <div class="column3">
            <br>
            <br>
            <p><strong>Wiener Konzerthaus</strong> </p>
            Das darauf folgende Konzert findet genau an G.Puccinis 100. Todestag statt. Ihm zu Ehren komponiert Christof Unterberger eine Hommage á Puccini, das selten gehörte Fagottkonzert seines Landsmannes G.Rossini erklingt, es spielt Benedikt Dinkhauser und mit “der italienischen” 4. Symphonie von F. Mendelssohn- Bartholdy beschließen wir das Jubiläumskonzert unter der Leitung von Jon Svinghammar.
        </div>
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
            Auferstehungssymphonie von Gustav Mahler - die 2. Symphonie - unter der Leitung von Michal Juraszek aufführen.
        </div>
    </div>

    
</body>
</html>
<br>
<br>

