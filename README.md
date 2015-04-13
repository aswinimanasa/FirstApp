# FirstApp
<!DOCTYPE html>
<html>
<head>

<script type="text/javascript">

function showAlert()
{
navigator.notification.alert('Hii,How Are You?','Greetings','Fine');	
}

function showBeep()
{
navigator.notification.beep(3);
}

function showVibrate() 
{
navigator.notification.vibrate(2000);
}

</script>


<meta charset="ISO-8859-1">
<title>Insert title here</title>
</head>
<body>
<input type="button" value="Show Alert" onclick="showAlert()"><br>
<input type="submit" value="Beep" onclick="showBeep()"><br>
<input type="submit" value="Vibration" onclick="showVibrate()"> 
</body>
</html>
