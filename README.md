<html>
  <head>
    <script type="text/javascript">
      function rjs(){
        document.location.href="./home.html";
      }
   </script>
  </head>
  <body onLoad="setTimeout('rjs()', 1)">
     <div>Dans 2 secondes vous allez être redirigé...</div>
    <input name="bouton_terminer" type="button" value="Terminer"
    onclick="rjs()">
  </body>
</html>
