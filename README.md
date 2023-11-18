<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <button onclick="myfunction()">get data</button>
    <p id="hello"></p>
    <table id="myTable" border="1px" >
        <tr>
          <td>name</td>
          <td>branch</td>
        </tr>
        <tr>
          <td>sita</td>
          <td>cse</td>
        </tr>
        <tr>
          <td>ritu</td>
          <td>it</td>
        </tr>
      </table>

    <script>
        function myfunction(){
            document.getElementById("hello").innerHTML="enter data";
            console.log("enter data");
            var table = document.getElementById("myTable");
  var row = table.insertRow(0);
  var col1= row.insertCell(0);
  var col2= row.insertCell(1);
  col1.innerHTML = "Name";
  col2.innerHTML = "branch";
  
}
        
        
    </script>
</body>
</html>
