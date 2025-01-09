Create a database with name bikerental

Run the script http://localhost/bikerental PHP

For Admin Panel

Open Your browser put inside browser “http://localhost/bikerental/admin”

USERNAME : purnendudutta521@gmail.com

PASSWORD : Purnendu521@


                                 You can replace the below code in: 'EDIT-VEHICLE.PHP"
<?php if($result->Vimage5=="")
	{
		Image 5<img src="img/vehicleimages/<?php echo htmlentities($result->Vimage5);?>" width="300" height="200" style="border:solid 1px #000">
		<a href="changeimage5.php?imgid=<?php echo htmlentities($result->id)?>">Change Image 5</a>
		</div>
	} 
else 
	{
		echo htmlentities("File not available");
	}
?>
