<!DOCTYPE html>
<html>
  <head>
    <script>
      function func()
      {
        var element= document.createElement("div");
        var node = document.createTextNode("New Element Added");
        element.appendChild(node);
        document.body.appendChild(element);
      }
    </script>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body onLoad="func();">
    <script src="script.js"></script>
  </body>
</html>
