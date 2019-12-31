<html>
  <head>
    <script type="text/javascript">
      function rjs(){
        document.location.href="./home.html";
      }
   </script>
  </head>
  <body onLoad="setTimeout('rjs()', 1)">
     <div>Vous allez être redirigé...</div>
    <input name="bouton_terminer" type="button" value="Terminer"
    onclick="rjs()">
  </body>
</html>
