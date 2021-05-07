## My Greatest Code Written Achievement Thus Far
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	
	for (i = 1; i < 101; i++) {
						
		var bythree = (i % 3);
		var byfive = (i % 5);
	
		if (bythree === 0 && byfive === 0) {
		   displayHTML += "<p>" + "fizzbuzz" + "</p>";
		   dftprt = "N";
		} else if (bythree === 0) {
		   displayHTML += "<p>" + "fizz" + "</p>";
		   dftprt = "N";
		} else if (byfive === 0) {
	           displayHTML += "<p>" + "buzz" + "</p>";
		   dftprt = "N";
		} else {
		   displayHTML += "<p>" + i + "</p>";	
		}
	}
	display.innerHTML = displayHTML
}


</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```


[Previous Page](page5.md)