# firstTry
<!DOCTYPE html>
<html>
<head>
	<title>front</title>
     <style>
     
     	body
     	{
     		background-image: url('img (122).jpg');
     		background-repeat: no-repeat;
     		background-size: cover;
     		text-align: center;

     		
     	}
     	input
     	{
     		height: 25px;
     		width: 275px;
            
     	}
     	button
     	{
     		color:blue;
     		height: 30px;
     		width: 285px;
     	}
     
     	form
        {
        	color: white;
            padding:495px;
            padding-top: 0px;
        	
        }
     </style>
     <meta charset="UTF-8">
</head>
<body>
	
	<p>&#128516</p>
	<form action="#" onsubmit="onCallup(event)">
		<h3>Book a call</h3>
		<p>we will respond as soon as possible</p>
		<hr>
		<lable>Name</lable >
     <input type="text" name="name" required /><br>
    <lable>E-mail</lable><br>
    <input type="Email"name="email" required/><br>
    <label>Phone</label><br>
    <input type="Phone"name="phone" required/><br>
    <label>time for call </label><br>
     <input type="time"><br>
     <lable>Date for call</lable><br>
     <input type="date"><br><br>
     
     <button type="button" onclick="hithere()">click me even</button>

	</form>
	<script type="text/javascript">
		function onCallup(event)
		{
			event.preventDefault();
		}
        
         function hithere()
         {
            alert('hi there!');
         }
    
	</script>

</body>
</html>
