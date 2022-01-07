
<h1>You have spent a few days in Argentina</h1>
<p>This page will help you get used to everyday life in Argentina</p>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 30.33%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "Table with vocab";
  display: table;
  clear: both;
}
</style>


<h2>Useful Vocab</h2>

<div class="row">
  <div class="column">
    <h2>Grocery Store</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Supermarkt.jpg" style="width:50%;">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myTable {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#myTable th, #myTable td {
  text-align: left;
  padding: 12px;
}

#myTable tr {
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  background-color: #f1f1f1;
}
</style>


<h2>Most Common Items</h2>

<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for items.." title="Type in a name">

<table id="myTable">
  <tr class="header">
    <th style="width:40%;">English</th>
    <th style="width:40%;">Spanish</th>
  </tr>
  <tr>
    <td>Orange</td>
    <td>Naranja</td>
  </tr>
  <tr>
    <td>Apple</td>
    <td>Manzana</td>
  </tr>
  <tr>
    <td>Banana</td>
    <td>Banana</td>
  </tr>
  <tr>
    <td>Cucumber</td>
    <td>Pepino</td>
  </tr>
  <tr>
    <td>Carrot</td>
    <td>Zanahoria</td>
  </tr>
  <tr>
    <td>Potatoes</td>
    <td>Papas</td>
  </tr>
  <tr>
    <td>Cabbage</td>
    <td>Repollo</td>
  </tr>
  <tr>
    <td>Lemon</td>
    <td>Limon</td>
  </tr>
  <tr>
    <td>Watermelon</td>
    <td>Sandía</td>
  </tr>
  <tr>
    <td>Pear</td>
    <td>Pera</td>
  </tr>
  <tr>
    <td>Grapes</td>
    <td>Uvas</td>
  </tr>
  <tr>
    <td>Tomatoes</td>
    <td>Tomates</td>
  </tr>
  <tr>
    <td>Olives</td>
    <td>Aceitunas</td>
  </tr>
  <tr>
    <td>Pepper</td>
    <td>Pimiento</td>
  </tr>
  <tr>
    <td>Strawberries</td>
    <td>Frutillas/Fresas</td>
  </tr>
  <tr>
    <td>Raspberries</td>
    <td>Frambuesas</td>
  </tr>
  <tr>
    <td>Lettuce</td>
    <td>Lechuga</td>
  </tr>
  <tr>
    <td>Melon</td>
    <td>Melón</td>
  </tr>
  <tr>
    <td>Aubergine/Eggplant</td>
    <td>Berenjena</td>
  </tr>
    <tr>
    <td>Kiwi</td>
    <td>Kiwi</td>
  </tr>
  <tr>
    <td>Peach</td>
    <td>Durazno</td>
  </tr>
  <tr>
    <td>Onion</td>
    <td>Cebolla</td>
  </tr>
  <tr>
    <td>Garlic</td>
    <td>Ajo</td>
  </tr>
  <tr>
    <td>Avocado</td>
    <td>Palta</td>
  </tr>
</table>

<script>
function myFunction() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>
  </div>
  
  <div class="column">
    <h2>SuperMarket</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/La_Anonima_San_Martin_de_los_Andes_3.jpg" style="width:50%;">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myTable {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#myTable th, #myTable td {
  text-align: left;
  padding: 12px;
}

#myTable tr {
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  background-color: #f1f1f1;
}
</style>


<h2>My Common Items</h2>

<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for items.." title="Type in a name">

<table id="myTable">
  <tr class="header">
    <th style="width:40%;">English</th>
    <th style="width:40%;">Spanish</th>
  </tr>
  <tr>
    <td>Pasta</td>
    <td>Pasta</td>
  </tr>
  <tr>
    <td>Pizza</td>
    <td>Pizza</td>
  </tr>
  <tr>
    <td>Hamburger</td>
    <td>Hamburguesa</td>
  </tr>
  <tr>
    <td>Cheese</td>
    <td>Queso</td>
  </tr>
  <tr>
    <td>Butter</td>
    <td>Manteca</td>
  </tr>
  <tr>
    <td>Bread</td>
    <td>Pan</td>
  </tr>
  <tr>
    <td>Sweets</td>
    <td>Dulces</td>
  </tr>
  <tr>
    <td>Drinks</td>
    <td>Bebidas</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>Leche</td>
  </tr>
  <tr>
    <td>Cereal</td>
    <td>Cereal</td>
  </tr>
  <tr>
    <td>Olive Oil</td>
    <td>Aceite de Oliva</td>
  </tr>
  <tr>
    <td>Sunflower oil</td>
    <td>Aceite de Girasol</td>
  </tr>
  <tr>
    <td>Toilet Paper</td>
    <td>Papel Higienico</td>
  </tr>
  <tr>
    <td>Salt</td>
    <td>Sal</td>
  </tr>
  <tr>
    <td>Sugar</td>
    <td>Asucar</td>
  </tr>
  <tr>
    <td>Suncream</td>
    <td>Crema Solar</td>
  </tr>
  <tr>
    <td>Red Meat</td>
    <td>Carne Roja</td>
  </tr>
  <tr>
    <tr>
    <td>Ckicken</td>
    <td>Pollo</td>
  </tr>
 <tr>
    <td>Lamb</td>
    <td>Cordero</td>
  </tr>
  <tr>
    <td>Salmon</td>
    <td>Salmón</td>
  </tr>
  <tr>
    <td>Sea Bass</td>
    <td>Lubina</td>
  </tr>
  <tr>
    <td>Cod</td>
    <td>Bacalao</td>
  </tr>
  <tr>
    <tr>
    <td>Pastries</td>
    <td>Facturas/Pasteles</td>
  </tr> 
  <tr>
    <td>Jam</td>
    <td>Mermelada</td>
  </tr>
  <tr>
    <td>A Fillet of...fish</td>
    <td>Un filete de (eg)Pescado</td>
  </tr>
  <tr>
    <td>One Kilogram of...</td>
    <td>Un kilo de...</td>
  </tr>
  <tr>
    <td>Cookies/Biscuits</td>
    <td>Galletitas</td>
  </tr>
  <tr>
    <tr>
    <td>Crisps</td>
    <td>Patatas Fritas</td>
  </tr> 
  <tr>
    <td>Chips</td>
    <td>Papas Fritas</td>
  </tr> 
</table>

<script>
function myFunction() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>
  </div>
  
  <div class="column">
    <h2>Ice Cream Flavours</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Ice_cream_with_whipped_cream%2C_chocolate_syrup%2C_and_a_wafer_%28cropped%29.jpg" style="width:50%;">
  </div>
</div>






