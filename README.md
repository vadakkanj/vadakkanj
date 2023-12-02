<html> 
<body>
<head>
<script>

 var clicks = 1
 ; 
 function onClick() 
 {
	 clicks += 1; 
	 document.getElementById("clicks").innerHTML = clicks; 
 };
  
</script>

<div align="center">
<H1 align="center"><b> clicking game by neo
</b> </h1>
<marquee behavior="scroll" direction="left">
By neo joshi
</marquee>
<body bgcolor="yellow" text="red">
<button type="button" onClick="onClick()">
Click to count 
</button> 
<p>Clicks: <a id="clicks">0</a></p>
</head>
</div>
</body>
</html><marquee behavior="scroll" direction="left">
By neo
