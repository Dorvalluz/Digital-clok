# Digital-clock
Um simples projeto de relógio digital.

<!DOCTYPE html> 
<html>
<head>
<title>Relogio do Durvas</title>
<script>  
             function displayTime() {
             var elt = document.getElementById("clock");
              var now = new Date();
              elt.innerHTML = now.toLocaleTimeString();
              setTimeout(displayTime, 1000);
              }
              window.onload = displayTime; 
              </script>
              <style>      
               #clock {        
               font: bold 24pt sans;  
                background: #ddf;  
                padding: 10px;    
                border: solid black 2px;  
                 border-radius: 10px; }
                </style> 
                </head>  
                <body>    
         <h1>Digital Clock Durvas </h1>
          <span id="clock"></span>
           </body> 
           </html>
