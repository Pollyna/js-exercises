<DOCTYPE html>
	<html>
		<head>
			<title>_LIFT_</title>
		</head>
		<body>
			<script>
				do{
					var apartment = +prompt('apartment number', 23);
					var floorNumber = Math.ceil(apartment / 3);
					var i = floorNumber;
						if(i%2 == 0) {
							alert('floor #' + i +' lets go!');
						}
						else if (confirm ('floor ' + i +' is not served, want to go floor ' + (i+1) +'?') == true) {
        					alert('lets go!');
    					}
						else {
       						alert ("leave the elevator car");
    					}
					}
				while(i<200);
				
			</script>
		</body>
	</html># js-exercises
