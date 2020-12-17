
<body style="background-color:green"> <!-- it is advised to not use inline styling -->
<h3 style="text-align:center; color:white"> Program to generate the Fibonacci Series </h3>
<script type="text/javascript">

var limit = prompt("Enter the limit 'n' to generate the fibonacci series:", " ");
var a = 0;
var b = 1;

document.write("<h3>The limit entered to generate the series is: " ,limit , "</br></h3>");
document.write("<h3>The fibonacci series : </h3>");
document.write("<h3>", a ," </h3>");
document.write("<h3>", b ," </h3>");
 
var i , c ;
for(i = 2 ; i < limit; i++)
{
	 c = a + b;
	 document.write("<h3>", c , " </h3>");
	 a = b;
	 b = c;
}
</script>
</body>
