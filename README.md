<!DOCTYPE html>  

<html>  

<head>  

</head>  

<body style = "text-align: center; font-size: 20px;">  

<h1> Welcome to the javaTpoint.com </h1>  

Enter a number: <input id = "number">  

<br><br>  

<button onclick = "fact1()"> Factorial </button>  

<p id = "res"></p>  

<script>  

function fact(num)   

{  

if (num == 0) {  

return 1;  

}  

else {  

return num * fact( num - 1 );  

}  

}  

function fact1()  
{
  

var num = document.getElementById("number").value;  

var f = fact(num);  

document.getElementById("res").innerHTML="The factorial of the number " + num + " is: " + f ;  

}  

</script>  

</body>  

</html>  
