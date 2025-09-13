---
marp: true
theme: gaia
class:
  - lead
  - invert
paginate: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;

    /* Center align content vertically */
    align-items: top;
  
  }
  img[alt~="center"] {
  display: block;
  margin: 0 auto;
  }
---
<!-- class: lead -->
# Wie Karaoke funktioniert

MRMCD 2025

nachtpfoetchen

---
<!-- class: default -->
# me
- played way too much karaoke while i should make slides
- enby das irgendwie gerne Karaoke Dinge tut
- Pronomen??? existieren vielleicht, idk, halp
- fedi? nachtpfoetchen@donotsta.re
# ow
Slides: https://github.com/Nachtpfoetchen/2025-MRMCD-Karaoke
Markdown für Marp

---
<!-- class: lead -->
# Was ist Karaoke?

---
<!-- class: default -->
<div class="columns">
<div>

![width:550px](Bilder/karaoke_demo_01.png)
Dancing Queen mp3+cdg
</div>
<div>

## Grundsätzlich
- Musik
- getimter Text?
- Viel Spaß
</div>
</div>

---
<!-- class: default -->
<div class="columns">
<div>

![width:550px](https://upload.wikimedia.org/wikipedia/en/f/f1/SingStar_screenshot.JPG)
Singstar
</div>
<div>

## Optional
- Videos
- Animation
- Tonhöhe
- Mikrofon
- Backing Vocals
- Songlisten-Management
</div>
</div>

---
# Größten technischen Änderungen

- Dateigröße
- Variable Tonhöhe
- Variables Tempo
- Spiele mit Punkten
- Spiele mit Lipsync
- Kataloggröße
- Automatische Entfernung der Backing Vocals

---
<!-- class: default -->
<div class="columns">
<div>

![width:550px](https://preview.redd.it/ld373rm65uo61.jpg?width=1080&crop=smart&auto=webp&s=bdf5dc4ecacd34cbcf2df1c90490ee5ab94774d4)
</div>

<div>

 # Karaoke Maschinen

- Maschienen zum Karaoke spielen
- Bildschirm
- Mikrophon
- Karaoke Booth
  </div>
</div>

---
<!-- class: default -->

# VHS, Laserdisc
<div class="columns">
<div>

![width:550px](https://i.ytimg.com/vi/TWRcpqAt57c/maxresdefault.jpg)
Laserdisk Karaoke Setup von Claudiu Dobondi youtube
</div>

<div>

- Video mit getimten Lyrics
- Verwendung von Videomaterial im Hintergrund
- Player, Bildschirm, Mikrofon
</div>
</div>

---

# CD+Graphics

<div class="columns">
<div>

![width:550px](Bilder/Bildschirmfoto_20250912_131731.png)
</div>

<div>

- Visualisierung im Subcode der CD
- Limitierung auf Bitmaps
- Hintergrund idr Einfarbig
- Viele Lieder auf einer Disc
- Bis heute kommerzieller Vertrieb

</div>
</div>

---

<div class="columns">

![height:400px center](Bilder/mr_entertainer_2024.jpg)
Mr. Entertainer CD+G Release

![height:400px center](Bilder/zoom_karaoke_2024_usb.jpg)
Zoom Karaoke USB Release



---


![height:640px center](https://external-preview.redd.it/OFpQaevzXLbM3gm0EyYpWbbN6cHBoQuW58QFwxrmtoE.jpg?width=1080&crop=smart&auto=webp&s=2f95a0d2b30a730b3d3b0a8a631d9d0bb29fe9f8)


---

# mp2/3/ogg/etc + cgd

<div class="columns">
<div>

![width:550px](Bilder/Screenshot_2025-09-12_at_13-24-05_Feature_Films.png)
</div>

<div>

- Umsetzung des Subcodes der CD+G als eigene binär Datei die parallel zum Playback abgespielt wird.
- Durch emule, p2p filesharing erstmals umfassende Kataloge
- Bis heute Kommerzieller Vertrieb
</div>
</div>

---

# Midi Karaoke

<div class="columns">
<div>

![height:450px](Bilder/Bildschirmfoto_20250912_163429.png)
</div>

- Lied wird in MIDI nach programmiert
- getimte Lyrics werden zum midi hinzugefügt
- kleine Dateigröße

---

![height:500 center](Bilder/Bildschirmfoto_20250912_174026.png)
Karaoke version: Medley ABBA - Medley Covers - Custom Backing Track MP3

---

# Spielekonsolen (Auswahl)

| Jahr | Konsole | Markt | Erweiterung | 
| --- | --- | --- | --- |
| 1987 | Famicon | Japan | Karaoke Studio |  
| 1992 | Sega Mega-CD | Japan | Sega Mega-CD Karaoke |
| 2004 | PS2 | Europe, Oceania | SingStar |
| 2014 | C64 | Worldwide |  International Karaoke+ |

---
<div class="columns">
<div>

![width:500 center](https://www.k-yen-team.fr/wp-content/uploads/2011/05/dckara.jpg)
Dreamcast Karaoke Erweiterung
[https://www.k-yen-team.fr/karaoke-sur-sega-dreamcast/]
</div>
<div>

![width:400 center](Bilder/famicom-karaoke-studio-1588187170-86.webp)
famicon Erweiterung

---

![width:800 center](https://www.lemon64.com/assets/images/games/screens/international_karaoke_plus/international_karaoke_plus_03.png)
C64 International Karaoke+

---
 
 # Singstar

<div class="columns">
<div>

![width:550px](https://upload.wikimedia.org/wikipedia/en/f/f1/SingStar_screenshot.JPG)

</div>
<div>

 - Release 2004
 - Weiterentwicklung des Spielprinzips durch Score
 - Große Verbreitung in Europa
 - teilweise Exklusive Videos
 - teilweise orginale Songs

</div>
</div>

---

# Ultrastar
<div class="columns">
<div>

![width:550px](https://upload.wikimedia.org/wikipedia/commons/b/b4/Ultrastar_082_pre-alpha_01.jpg)
Gameplay usdx 0.8.2

</div>

- Nachbau der Mechaniken von Singstar
- Große Community, Tooling, Torrents. etc. für Songs
- Offenes Format zur Erstellung von Songs

---

# Projekte um Ultrastar

| Jahr | Open Source|  Projektname |
| --- | --- | --- |
| 2004 | ja (ursprünglich) | Ultrastar |
| 2007 | ja | Performous |
| 2007 | ja | Ultrastar Deluxe | 
| 2009 | ja | Yass Karaoke Editor |
| 2011 | ja | Fork Ultrastar World Party |
| 2020 | ja | Ultra Star Play |
| 2023 | nein | Melody Mania |

---
<!-- class: lead -->
![width:760px](Bilder/Allkaraokeparty.png)

---
<!-- class: default -->

# Cloud

<div class="columns">
<div>

![width:550px](Bilder/karafun_console.png)

</div>

<div>

- Karafun
- Spotify
- Apple Music
- youtube
- smule
- Starmaker
</div>

</div>

---

# Just Sing

- 2016 PS4 XBox 1
- Weiterentwicklung des Spielprinzips durch Lipsync über einen Smartphone Companion / Kinect / Playstation Camera

# Let's Sing

 - Ähnliches Spielprinzip wie Singstar, just sing
 - Erster Release 2012 auf Wii

---

# Karaoke Mugen

![width:800px center ](https://mugen.karaokes.moe/images/presentation.png)

---

# Karaoke Player linux

- mp3+cdg support in ffmpeg
- Spivak
- Ultrastar*
- Webbrowser (All Karaoke party, youtube, karafun, etc)
- Konsolenemulation
- Karaoke Mugen

---

# Karaoke Suchmaschienen

<div class="columns">
<div>

![width:200px](https://www.karaokenerds.com/Content/Images/rev1.png)

![width:200px](https://karatrack.com/wp-content/uploads/2022/07/Karatrack-logo.png)

![width:200px](http://www.icroons.com/images/logos/iCroons_400w.jpg)

</div>

<div>

- https://www.karaokenerds.com/
- http://www.icroons.com/
- https://karatrack.com
- https://db.openkj.org/

</div>

</div>

---

# Hardware

<div class="columns">
<div>

![height:500px](Bilder/Bildschirmfoto_20250913_112654.png)

</div>
<div>

- Mikrofon bei Bedarf
- Mixer
- Spzielle Karaoke Hardware / Software kann ggf Tonhöhe und Tempo variieren
- Bildschirm
- Boxen

</div>
</div>

---

# Bild-Quellen

später auf github