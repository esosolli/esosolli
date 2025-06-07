<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mini project</title>
    <link rel="stylesheet" href="style.css">
    <script src="index.js"></script>
    <link rel="JavaScript" href="index.js"
   
</head>
<body>
    <h1>Calculator App</h1>
    <div class="container">
        
        <form action="">
        <div class="screen">
            <input type="text" name="display" id="display">
        </div>
        <div class="numpad">
        <div>
            <input class="btn" type="button" value="0" onclick="display.value +='0'">
            <input class="btn" type="button" value="C" onclick="display.value =``"> 
            <input class="btn" type="button" value="/" onclick="display.value +='/'" class="operator">
       <input class="btn" type="button"value="=" 
onclick="display.value=eval(display.value)"class="equal">
        </div>
        <div>
            <input class="btn" type="button" value="7" onclick="display.value +='7'">
            <input class="btn" type="button" value="8" onclick="display.value +='8'">
            <input class="btn" type="button" value="9" onclick="display.value +='9'">
            <input class="btn" type="button" value="*" onclick="display.value +='*'" class="operator">
        </div>
        <div>
   <input class="btn" type="button" value="4" onclick="display.value +='4'">
            <input class="btn" type="button" value="5" onclick="display.value +='5'">
            <input class="btn" type="button" value="6" onclick="display.value +='6'">
            <input class="btn" type="button" value="-" onclick="display.value +='-'" class="operator">
        </div>
        <div>
            <input class="btn" type="button" value="1" onclick="display.value +='1'">
            <input class="btn" type="button" value="2" onclick="display.value +='2'">
            <input class="btn" type="button" value="3" onclick="display.value +='3'">
            <input class="btn" type="button" value="+" onclick="display.value +='+'" class="operator">
        </div>
        <div>
        </div>
        </div>
        </form>
    </div>
    <footer>Assignment by <strong >3MTT</strong>. Coded by <strong>FE/23/42848587</strong>
    </footer>
   </body>
   </html>



CSS Styling 

body {
    width: 100%;
    background-color:#5d5d5d7 ;
    font-weight: 700;
    font-family: 'lucia sans lucia sans regular;
    text-align: center;
    color: rgb(25, 35, 44);;
}
.container {
    margin: 15% auto;
    width: fit-content;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    border-radius: 7%;
    background-color: white;
    padding: 6%;
    box-shadow: grey;
    border: 0px;
}
#display {
    
    width: 300px;
    margin: 15px 0px;
    border-radius: 8%;
    border: 0px;
    background-color: #8098ff;
    font-size: 50px;
    font-weight: 700;
    font-family: 'lucia sans lucia sans regular;
    color: aquamarine;
}
.btn {
    height: 60px;
    width: 60px;
    padding: 3%;
    margin: 8px;
    font-size: 30px;
    font-weight: 700;
    font-family: 'lucia sans lucia sans regular;
    color: aquamarine;
    background-color: #8098ff;
    border-radius: 20%;
    border: 0px;
   
}
}
form .screen{
    display: flex;
    justify-content: flex-end;
}
form .screen input{
    text-align: right;
}
footer{
    color:rgb(25, 35, 44);
    font-weight: 700;
    font-family: 'lucia sans lucia sans regular;
    text-align: center;
}
@media only screen and (min-width: 768px){
    .container{
        padding: 45px;
        margin: 10% auto;
    }
}


JavaScript 

  Calculate() 
  {
     let result;
     const prev = parseFloat(this.previousInput);
     const current= parseFloat(this.currentInput);
     
     if (this.operation==='-') {
     result = prev - current;
         
     }
     else if (this.operation === '+') {
         result = prev + current;
     }
     else if (this.operation==='*') {
         result = prev * current;
     }
     else if (this.operation ==='/') {
     if (current === 0) {
         alert("cannot divide by zero");
         return;
     }
         result = prev / current;
     }
 }