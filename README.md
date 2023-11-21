<center>

# Überschrift

TextTextTextText
**TextText**
</center>


<h2>Unterkapitel:</h2>

TextText
TextText
<p align="center">Mein Projekt</p>
<p align="center">Ein tolles Open-Source-Projekt für GitHub-Nutzer.</p>

<span style="color: red;">Dies ist roter Text</span>


<font color="#000080">
<h3>Unterunterkapitel</h3>

TextText
Text
</font>
<font color="#CCCCFF">
<h3>Unterunterkapitel</h3>

TextText
Text
</font>
<font color="#000080">



<h2>Unterkapitel:</h2>

TextText
TextText

<font color="#8b0000">
<h3>Unterunterkapitel</h3>

TextText
Text
</font>
<font color="#000080">
<h3>Unterunterkapitel</h3>

TextText
Text
</font>
<font color="#000080">

<br>
<center>
    <b>
        Anmerkung!
        <br>
        <br>
        
    
</center>
<h1>Unterkapitel:</h1>

tttttttt


# Dies ist ein Haupttitel (H1)

## Dies ist eine Unterüberschrift (H2)

### Dies ist eine Unterüberschrift (H3)

#### Dies ist eine Unterüberschrift (H4)

##### Dies ist eine Unterüberschrift (H5)

<h1>Dies ist ein Haupttitel</h1>

<h2>Dies ist eine Unterüberschrift</h2>

<h3>Dies ist eine Unterüberschrift</h3>

<h4>Dies ist eine Unterüberschrift</h4>
<font color="#000080">
<details>
  <summary>Klick mich, um mehr zu erfahren!</summary>

  Hier ist der Inhalt, der in der klapplaren Box angezeigt wird. Dies kann beliebiger Markdown-Text sein.

  Zum Beispiel eine Liste:
  - Punkt 1
  - Punkt 2
  - Punkt 3
</details>
</font>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .accordion {
      background-color: #eee;
      color: #333;
      cursor: pointer;
      padding: 18px;
      width: 100%;
      text-align: left;
      border: none;
      outline: none;
      transition: 0.4s;
    }

    .panel {
      padding: 0 18px;
      display: none;
      background-color: white;
      overflow: hidden;
    }
  </style>
</head>
<body>

<button class="accordion">Abschnitt 1</button>
<div class="panel">
  <p>Inhalt für Abschnitt 1...</p>
</div>

<button class="accordion">Abschnitt 2</button>
<div class="panel">
  <p>Inhalt für Abschnitt 2...</p>
</div>

<script>
  var acc = document.getElementsByClassName("accordion");
  var i;

  for (i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var panel = this.nextElementSibling;
      if (panel.style.display === "block") {
        panel.style.display = "none";
      } else {
        panel.style.display = "block";
      }
    });
  }
</script>

</body>
</html>



<style>
  details {
    border: 1px solid #ddd;
    padding: 5px;
    margin-bottom: 10px;
    border-radius: 5px;
  }
  summary {
    cursor: pointer;
  }
</style>

<details>
  <summary>Bereich 1</summary>
  
  Inhalt des Bereichs 1.

</details>

<details>
  <summary>Bereich 2</summary>
  
  Inhalt des Bereichs 2.

</details>

<details>
  <summary>Bereich 3</summary>
  
  Inhalt des Bereichs 3.

</details>

