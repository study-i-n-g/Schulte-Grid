# Schulte-Grid
train your concentration
<html>
    <head><title>number memory</title></head>
    <body>
        <canvas id="board" width="600px" height="600px"></canvas>
        <script>
            var board=document.getElementById("board");
            var table=board.getContext("2d");
           for (var i=0;i<5;i++){
                table.beginPath();
                table.moveTo(150*i,0);
                table.lineTo(150*i,600);
                table.moveTo(0,150*i);
                table.lineTo(600,150*i);
                table.stroke();            
            }
        </script>
    </body>
</html>
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
