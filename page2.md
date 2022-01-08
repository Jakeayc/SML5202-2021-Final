---
title: Page2
---  
<style>
h1 {text-align: center;}
h2 {text-align: center;}
  div {text-align: center;}
p {text-align: center;}
</style>


<h1>You have just landed in Argentina</h1>

  <p>Here is some useful words you can ask or look for to navigate around the airport</p>
  
  <title>Sort a HTML Table Alphabetically</title>
<style>
table {
  border-spacing: 0;
  width: 100%;
  border: 1px solid #ddd;
}

th, td {
  text-align: left;
  padding: 16px;
}

tr:nth-child(even) {
  background-color: #f2f2f2
}
</style>

<h2>Useful words to know at an Argentine airport</h2>
<p>Click the button to sort the table alphabetically in English:</p>
<p><button onclick="sortTable()">Sort</button></p>

<table id="myTable">
  <tr>
    <th>English</th>
    <th>Spanish</th>
  </tr>
  <tr>
    <td>Toilets</td>
    <td>Baños</td>
  </tr>
  <tr>
    <td>Taxi</td>
    <td>Taxi (same word)</td>
  </tr>
  <tr>
    <td>Bus Station</td>
    <td>Estación de Colectivo</td>
  </tr>
  <tr>
    <td>Train Station</td>
    <td>Estación de Tren</td>
  </tr>
  <tr>
    <td>Underground Station</td>
    <td>Estación de Subte/Metro</td>
  </tr>
  <tr>
    <td>Information desk</td>
    <td>Estación de Información</td>
  </tr>
  <tr>
    <td>Currency Exchage</td>
    <td>Cambio de Moneda</td>
  </tr>
  <tr>
    <td>Lost Property</td>
    <td>Oficina de Objetos Perdidos</td>
  </tr>
</table>

<script>
function sortTable() {
  var table, rows, switching, i, x, y, shouldSwitch;
  table = document.getElementById("myTable");
  switching = true;
  /*Make a loop that will continue until
  no switching has been done:*/
  while (switching) {
    //start by saying: no switching is done:
    switching = false;
    rows = table.rows;
    /*Loop through all table rows (except the
    first, which contains table headers):*/
    for (i = 1; i < (rows.length - 1); i++) {
      //start by saying there should be no switching:
      shouldSwitch = false;
      /*Get the two elements you want to compare,
      one from current row and one from the next:*/
      x = rows[i].getElementsByTagName("TD")[0];
      y = rows[i + 1].getElementsByTagName("TD")[0];
      //check if the two rows should switch place:
      if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
        //if so, mark as a switch and break the loop:
        shouldSwitch = true;
        break;
      }
    }
    if (shouldSwitch) {
      /*If a switch has been marked, make the switch
      and mark that a switch has been done:*/
      rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
      switching = true;
    }
  }
}
</script>
  
  <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>

  
  
  
<h2>Taxi Scenarios</h2>

<p>This is an exercise to prepare you to communicate with taxi drivers in Argentina as there could be misunderstandings and confusions</p>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Taxi_in_Buenos_Aires.jpg/512px-Taxi_in_Buenos_Aires.jpg" alt="Taxi in Buenos Aires" style="width:50%;">


<p>Firstly, you will have to <strong>listen to the audio</strong> as many times as you would like. Then <strong>drag the questions and their translations</strong> in the order they are said</p>
  
 
<audio controls>
  <source src="https://jakeayc.github.io/SML5202-2021-Final/audio/Taxi.mp3" type="audio/mpeg">
</audio>

<iframe src="https://h5p.org/h5p/embed/1240602" width="1090" height="467" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Taxi scenario"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<p>Please watch this video by OuinoLanguages on conversations in a Taxi, if you feel you need more help in this area</p> 
  <iframe width="560" height="315" src="https://www.youtube.com/embed/pDEHxG4tKvo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
  <p><a href="https://www.ouinolanguages.com/spanish/">Or visit OuinoLanguages website!</a></p>


  
