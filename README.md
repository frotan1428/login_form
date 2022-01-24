

 
<!DOCTYPE html>
<html>
<head>
	
	<link rel="stylesheet" href="css/bootstrap.min.css"/>
		
				<script src="js/bootstrap.min.js"></script>
					<link rel="stylesheet" href="css/adminstyle.css"/>
		<link rel="stylesheet" href="Include/Publicstyle.css"/>
		<style type="text/css">
			.Feildinfo{
				color: rgb(254,147,34);
				font-size: 20px;
				font-family: sans-serif;
			}
		</style>
</head>

<body>
 	<div class="container-fluid">

 			<div class=" col-sm-offset-4 col-sm-4">
 				<h1 style="color:blue; text-align: center;">Admin Page</h1>

 				<br>
 				<br>
 				  

 						
			     </div>
			     <h2 style="text-align: center;">Welcom Back!</h2>
 				 <form action="Login.php" method="Post">
				  <div class="form-group">
				    <label for="Username" class="Feildinfo">Username</label>
				    <div class="input-group">
				     <span class="input-group-addon">
				    	<span class="glyphicon glyphicon-envelope"></span>
				    </span>
				    <input type="Text" class="form-control" name="Username" id="Username" placeholder="Username">
				  </div>
				</div>

				  <div class="form-group">
				    <label for="Username" class="Feildinfo">Password</label>
				    <div class="input-group">
				    	 <span class="input-group-addon">
				    		<span class="glyphicon glyphicon-lock text-primary"></span>
				    </span>
				    <input type="Password" class="form-control" name="Password" id="Password" placeholder="Password">
				    
				  </div>
				</div>
 				 <button type="submit" class="btn btn-success btn-block" name="Login" 
 				 value="Login">Login</button>
				</form>
			</div>

 	</div>
</body>
</html>
