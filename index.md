<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

	<title>Login/Drug_store</title>

	<link href="css/bootstrap.min.css" rel="stylesheet">
	<link href="css/style.css" rel="stylesheet">
    <!--<script src="https://code.jquery/jquery-3.1.0.min.js"> </script>-->
	<script type="text/javascript" src="js/voting.js"></script>
</head>
<body>
 <nav class="navbar navbar-default ">
      <div class="container">
        <div class="navbar-header">
          <a class="navbar-brand" href="#" id="maintitle">Drug Store management system</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">

        <a href="admin.html">  </a>

        </div>
      </div>
    </nav> 

 <div class="container" style="margin-top:50px;">
	      <h1 class="col-md-offset-4">Login/Register</h1>
	         
     </div>
 
  <section id="main">

               <div class="container">

                <div class="row">

                    <div class="col-md-6 col-md-offset-4">
                      <form id="login" action="nurseboard.html" class="well">
                      
                        <div class="form-group">
                            <label> Nurse Id</label>
                            <input type="Number" class="form-control" placeholder="nurse Id" name="rollnumber">
                        </div>

                        <div class="form-group">
                            <label> Pass Word </label>
                            <input type="password" class="form-control" placeholder="password" name="password">
                        </div>
                        <button type="submit" class="btn btn-success" name="signin" > Sign in</button>
                        <a type="submit" class="btn btn-success" name="signup" data-toggle="modal" data-target="#addnurse" href="#"> <span class="glyphicon glyphicon-user"> </span> Register </a>
                        
                      </form>


                    </div>
                </div>
                
             </div>

        </section> 

        <!-- THIS IS THE MODAL SECTION ADDNURSE-->

               <div class="modal fade" id="addnurse" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
		  <div class="modal-dialog" role="document">
		    <div class="modal-content">
		      <form>
		          <div class="modal-header">
		              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
		              <h4 class="modal-title" id="myModalLabel">Nurse Information</h4>
		           </div>
		                <div class="modal-body">
		                 
		                  <form id="signup" action="nurseboard.html" class="well">

	                       <div class="form-group">
	                            <label>Frist name</label>
	                            <input type="text" class="form-control" placeholder="username" name="username">
	                        </div>

	                         <div class="form-group">
	                            <label> last name</label>
	                            <input type="text" class="form-control" placeholder="email" name="email">
	                         </div> 

	                        <div class="form-group">
	                            <label> ID</label>
	                            <input type="Number" class="form-control" placeholder="Nurse Id" name="rollnumber">
	                        </div>

                        <div class="form-group">
                            <label> Pass Word </label>
                            <input type="password" class="form-control" placeholder="choose password" name="password">
                        </div>
    
                      </form>  


	                <div class="modal-footer">               
	                  <button type="submit" class="btn btn-success"> <span class="glyphicon glyphicon-hand-right"></span> Register here </button>
	                </div>
             </div>
        </form>
    </div>
  </div>
</div>

                

     
<!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"> </script>

 </body>
</html>