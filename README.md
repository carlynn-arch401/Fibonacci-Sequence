

<body style= "background-image: url('golden-ratio.jpg');">
<h1 style="color: ivory; text-align: center;"> The Fibonacci Sequence </h1>

<script type="text/javascript">

var limit = prompt("Enter the desire range of the series:", "");
var f1=0;
var f2=1;

document.write("<h3>The limit entered to generate the fibonacci series is: ",limit, "<br/></h3>");
document.write("<h3>The fibonacci series : </h3>");
document.write("<h3>",f1," <h3>");
document.write("<h3>",f2," </h3>");
 
var i,f3;
for(i=2; i<limit; i++)
{
	 f3=f1+f2;
	 document.write("<h3>",f3," </h3>");
	 f1=f2;
	 f2=f3;
}
</script>
</body>
