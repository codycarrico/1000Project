## FizzBuzz

[Home](https://github.com/codycarrico/1000Project/blob/main/README.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Navigation](https://github.com/codycarrico/1000Project/blob/main/Navigation.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[About Me](https://github.com/codycarrico/1000Project/blob/main/About%20Me.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Resume](https://github.com/codycarrico/1000Project/blob/main/Resume.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FizzBuzz](https://github.com/codycarrico/1000Project/blob/main/FizzBuzz.md)

<br>

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
	for (i = 0; i < 100; i++) {
		if (i % 15 == 0)
		displayHTML += "FizzBuzz\n";
		else if (i % 3 == 0)
		displayHTML += "Fizz\n";
		else if (i % 5 == 0)
		displayHTML += "Buzz\n";
		else displayHTML += i+"\n";
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
