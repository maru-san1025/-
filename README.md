[11.html](https://github.com/user-attachments/files/25142908/11.html)
<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charaset = "uf-8">
        <title>11</title>
        <style>
            #parent{
                width:300px;
                height:300px;
                border: 1px solid blue;
                position: relative;
                margin: auto;
                
            }
            .child{                
                width: 100px;
                height: 100px;
                border: 1px solid red;
                background-image: url(7560a.png);
                background-size: 100%;
                            }
            .center{
                position:absolute;
                top: 0px;
                left: 0px;
                right: 0px;
                bottom: 0px;
                margin: auto;
            }    
            #parent{
                transform-style: preserve-3d;
                perspective: 300px;
            }
            #child1{
               animation: anime1 3s linear 0s infinite normal both;
            }
            @keyframes anime1{
                0%{rotate:y 0deg;}
                100%{rotate:y 360deg;}
            }
              
            
        </style>
        </head>
        <body>
            <div id="parent">
                <div class = "child center"
                id = "child1"></div>
             
            </div>
        </body>
</html>
<img width="500" height="500" alt="7560a" src="https://github.com/user-attachments/assets/6eddde0e-c0d2-4589-9e47-2d2cda7d719b" />
<img width="500" height="500" alt="7560a" src="https://github.com/user-attachments/assets/95980f12-3eeb-47f3-b2d3-6c27bba47ca3" />
