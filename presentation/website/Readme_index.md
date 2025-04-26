### Code

Es folgt eine detaillierte Beschreibung des Codes den man in den Dateien des Projekts findet. Nähere Beschreibungen der Projektstruktur, der Zielsetzung und der verwendeten Sprachen sind in der Projektbeschreibung.md zu finden!


## Allgemeins zur Datei index.html

- Dateiname :  index.html
- Sprache   :  HTML5
- Ziel      :  Eine Simple Landing Page mit Weiterleitung an ein Login-Formular


# Struktur und Funktionsweise


<!DOCTYPE html>                         # Das ist der Standard HTML Header zur Identifizierung der Datei
<html lang="en">                        # globaler Bezeichner für die Sprache
<head>                                  
<title>W3.CSS Template</title>          # Titel der Website
<meta charset="UTF-8">                  # Definierung der benutzten Zeichen

# Dependencies, müssen eingebunden werden für Grafiken und Fonts

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
# Beschreibung der Schriftarten und ihrer Styles
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
.w3-bar,h1,button {font-family: "Montserrat", sans-serif}
.fa-anchor,.fa-coffee {font-size:200px}
</style>
</head>

# Navbar 


<!-- Navbar -->
<div class="w3-top">  # Fixierte Navbar am oberen Bildschirmrand

  <div class="w3-bar w3-red w3-card w3-left-align w3-large">  # Hauptleiste in Rot mit Schatteneffekt und linksbündigen Elementen

    <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-red"
       href="javascript:void(0);"
       onclick="myFunction()"
       title="Toggle Navigation Menu">
       <i class="fa fa-bars"></i>
    </a>  # Hamburger-Menü-Icon für kleine Bildschirme, aktiviert per JavaScript die mobile Navigation

    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-white">Home</a>  # Aktiver Home-Link mit weißem Hintergrund

  </div>

  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium w3-large">
  </div>  # Verstecktes mobiles Navigationsmenü, wird über JavaScript angezeigt
</div>


# Body


<!-- Header -->
<header class="w3-container w3-red w3-center" style="padding:128px 16px">  # Großer, roter Header-Bereich mit zentriertem Text und großzügigem Innenabstand
  <h1 class="w3-margin w3-jumbo">Hier könnte ihre Werbung stehen!</h1>      # Hauptüberschrift mit großem Schriftstil
  <p class="w3-xlarge">Ich brauche 1 Million Euro</p>                      # Untertitel im XL-Stil

  <!-- Der Button ist jetzt ein Link -->
  <a href="andereSeite.html">                                              # Link zur Weiterleitung auf eine andere HTML-Seite
    <button class="w3-button w3-black w3-padding-large w3-large w3-margin-top">Get Started</button>  # Schwarzer, großer Button
  </a>
</header>

<!-- First Grid -->
<div class="w3-row-padding w3-padding-64 w3-container">  # Erster Inhaltsblock mit Abstand außen (padding)
  <div class="w3-content">                              # Zentrierter Container für Inhalt mit fixer Maximalbreite
    <div class="w3-twothird">                           # Zweidrittel der Breite für Text
      <h1>Lorem Ipsum</h1>                              # Abschnittsüberschrift
      <h5 class="w3-padding-32">Lorem ipsum ...</h5>    # Einführungstext mit Abstand innen
      <p class="w3-text-grey">Lorem ipsum ...</p>       # Grauer Fließtext mit Blindtext (Platzhalter)
    </div>

    <div class="w3-third w3-center">                    # Ein Drittel der Breite für Symbol
      <i class="fa fa-anchor w3-padding-64 w3-text-red"></i>  # Ankersymbol aus Font Awesome, rot und mit Innenabstand
    </div>
  </div>
</div>

<!-- Second Grid -->
<div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">  # Zweiter Inhaltsblock mit hellem Hintergrund
  <div class="w3-content">                                             # Gleiche Struktur wie oben
    <div class="w3-third w3-center">                                   # Symbol auf der linken Seite
      <i class="fa fa-coffee w3-padding-64 w3-text-red w3-margin-right"></i>  # Kaffeesymbol mit roter Farbe und rechtem Außenabstand
    </div>

    <div class="w3-twothird">                                          # Zweidrittel des Bereichs für Text
      <h1>Lorem Ipsum</h1>                                             # Abschnittsüberschrift
      <h5 class="w3-padding-32">Lorem ipsum ...</h5>                   # Einführungstext
      <p class="w3-text-grey">Lorem ipsum ...</p>                      # Grauer Fließtext mit Platzhaltertext
    </div>
  </div>
</div>

<div class="w3-container w3-black w3-center w3-opacity w3-padding-64">  # Schwarzer Bereich mit Transparenz und zentriertem Text
  <h1 class="w3-margin w3-xlarge">Quote of the day: live life</h1>     # Zitat im XL-Stil als Abschluss
</div>
