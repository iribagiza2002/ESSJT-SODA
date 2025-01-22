<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body><p id="forloop"></p>
    <script>
        var text ="";
        var x =1;
        for(x =1; x<100; x++) {
            text +="the number is" +x+ "<br>"
            if(x==30){
            break;    
            }
        document.getElementById("forloop").innerHTML=text;    
        }
    </script>
    
</body>
</html>
# ESSJT-SODA