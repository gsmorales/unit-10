# unit-10
CS 81
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("#animate_button").click(function(){
$("#animate_div").animate({fontSize: "100px"}, "slow");
});
});
</script>
</head>
<body>

<div id="animate_div">
Darth Vader
</div>

<button id="animate_button">Animate</button>

</body>
</html>
