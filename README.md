<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charaset = "uf-8">
        <title>15-3</title>
        <style>
        canvas {
            border: 1px solid gray;
        }
        </style>
        </head>
        <body>  
          <p><canvas id= "c1" width = "300"
        height = "300"></canvas></p> 
        <script>
            var c1 = document.getElementById("c1");
            var ctx1 = c1.getContext("2d");

            ctx1.beginPath();
            ctx1.moveTo(150,50,);
            ctx1.lineTo(50,250);
            ctx1.lineTo(250,250);
             ctx1.closePath();
            ctx1.fillStyle="red";
            ctx1.fill();

        </script>   

        </body>
</html>
