<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Counter</title>
    <link rel="stylesheet" href="button .css">
    
</head>
<body style="background-color: #16667E;">
    <h1>counter</h1>
    <p id="number">0</p>
   <div class="buttoncon">
        <button onclick="ultraminus()">-100</button>
        <button onclick="decrement()">-</button>
        <button onclick="reset()">reset</button>
        <button onclick="increment()">+</button>
        <button onclick="Ultraplus()">+100</button>
        
    </div>
    <script>
        const counter = document.getElementById("number");
        function increment(){
            const num = parseInt(counter.innerHTML);
            counter.innerHTML = num + 1;
        }

        function decrement(){
            const num = parseInt(counter.innerHTML);
            counter.innerHTML= num - 1; 
        }
        function reset(){
            counter.innerHTML= 0;
        }
        function Ultraplus(){
            const num = parseInt(counter.innerHTML);
            counter.innerHTML = num + 100;
        }
        function ultraminus(){
            const num = parseInt(counter.innerHTML);
            counter.innerHTML= num - 100; 
        }
        
    </script>
</body>
