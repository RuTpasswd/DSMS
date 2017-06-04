<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

	<title>Nurse Dashboard </title>

	<link href="css/bootstrap.min.css" rel="stylesheet">
	<link href="css/style.css" rel="stylesheet">
    <!--<script src="https://code.jquery/jquery-3.1.0.min.js"> </script>-->
	<script type="text/javascript" src="js/voting.js"></script>
</head>

<body>
 <nav class="navbar navbar-default ">
      <div class="container">
        <div class="navbar-header">
          <a class="navbar-brand" href="#" id="maintitle">Drug Store Mangement system </a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">

        <a href="admin.html">  </a>

        </div>
      </div>
    </nav> 
   
    <section id="main" style="margin-top:100px;">

      <div class="container">
             
        <div class="row">
               
         <div class="col-md-12">
             
             <!-- WEBSITE OVERVIEW-->

                   <div class="panel panel-default">
                    
                  <h3 class="col-md-offset-3"> <span class="glyphicon glyphicon-cog" aria-hidden="true"></span> Dashboard|<small> System Management</small> </h3> 
                        <div class="panel-heading main-color-bg"> <h3 class="panel-title"></h3> </div>

                        <div class="panel-body col-md-offset-2">
                          
                          <div class="col-lg-3" data-toggle="modal" data-target="#billform" >
                            <a href="#" style="text-decoration:none;"><div class="well dash-box">
                                <h2> <span class="glyphicon glyphicon-user" aria-hidden="true"></span> <h2>
                                <h3>SALING</h3>
                              </div> </a>
                           </div>

                          
                          <div class="col-lg-3">
                            <a data-toggle="modal" data-target="#recordform" href="#" style="text-decoration:none;"><div class="well dash-box">
                               <h2> <span class="glyphicon glyphicon-pencil" aria-hidden="true"></span> <h2>
                               <h3>Recording</h3>
                             </div> </a>
                          </div> 


                           <div class="col-lg-3">
                              <a href="stock.html" style="text-decoration:none;"> <div class="well dash-box">
                                 <h2> <span class="glyphicon glyphicon-stats" aria-hidden="true"></span> <h2>
                                 <h3> Check Stock </h3>
                               </div> </a>
                            </di>
                           

                          </div>

                        </div>
              

        <!-- LATEST USERS-->

              </div>
            </div> 
          </div> 

 </div>

</section>

  <footer class="footer text-center" style="padding:10px;background:;">
      <h3 style="color:black;font-size:20px;color:lightgrey;">Drug Store.&copy 2017 <small> Powered by ICT Club.</small>    </h3>          
     </footer>


     <!-- This is the Billing form modal  -->

    <div class="modal fade" id="billform" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
        <div class="modal-dialog" role="document">
          <div class="modal-content">
            <form>
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <h4 class="modal-title" id="myModalLabel">Billing Form</h4>
                 </div>
                      <div class="modal-body">
                       
                        <form id="signup" action="index.html" class="well">

                           <div class="form-group">
                                <label>Item name </label>
                                <input type="text" class="form-control" placeholder="item name" name="item_name">
                            </div>

                             <div class="form-group">
                                <label>Item ID</label>
                                <input type="text" class="form-control" placeholder="item Id" name="item_ID">
                             </div> 

                            <div class="form-group">
                                <label>Category </label>
                                <input type="text" class="form-control" placeholder="category" name="category">
                            </div>

                           <div class="form-group">
                               <label> Quantity</label>
                               <input type="number" class="form-control" placeholder="Quantity" name="quantity">
                           </div>

                           <div class="form-group">
                               <label>Price</label>
                               <input type="number" class="form-control" placeholder="Quantity" name="quantity">
                           </div>

                           <div class="form-group">

                               <label> Insurance</label>
                                <select class="form-control">
                                  <option value="rama"> RAMA</option>
                                  <option value="radiant"> Radiant</option>
                                  <option value="soras"> SORAS</option>
                                  <option value="ur"> UR</option>
                                  <option value="other"> Other</option>
                                </select>
                           </div>

                           <div class="form-group">
                               <label>Total Amount</label>
                               <input type="number" class="form-control" placeholder="Amount" name="amount">
                           </div>
       
                         </form>  


                    <div class="modal-footer">               
                      <button type="submit" class="btn btn-success"> <span class="glyphicon glyphicon-hand-right"></span> Print</button>
                    </div>
                </div>
           </form>
       </div>
     </div>
   </div>

   <!-- This is the Recording form -->
   
    <div class="modal fade" id="recordform" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
        <div class="modal-dialog" role="document">
          <div class="modal-content">
            <form>
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <h4 class="modal-title" id="myModalLabel"> Entry Record Form</h4>
                 </div>
                      <div class="modal-body">
                       
                        <form id="signup" action="index.html" class="well">

                           <div class="form-group">
                                <label>Item name </label>
                                <input type="text" class="form-control" placeholder="item name" name="item_name">
                            </div>

                             <div class="form-group">
                                <label>Item ID</label>
                                <input type="text" class="form-control" placeholder="item Id" name="item_ID">
                             </div> 

                            <div class="form-group">
                                <label>Category </label>
                                <input type="text" class="form-control" placeholder="category" name="category">
                            </div>

                           <div class="form-group">
                               <label> Quantity</label>
                               <input type="number" class="form-control" placeholder="Quantity" name="quantity">
                           </div>

                           <div class="form-group">
                               <label>Price</label>
                               <input type="number" class="form-control" placeholder="Quantity" name="quantity">
                           </div>

                           <div class="form-group">
                               <label>Selling Price</label>
                               <input type="number" class="form-control" placeholder="Quantity" name="quantity">
                           </div>
            

                           <div class="form-group">
                               <label>Total Amount</label>
                               <input type="number" class="form-control" placeholder="Amount" name="amount">
                           </div>
       
                         </form>  


                    <div class="modal-footer">               
                      <button type="submit" class="btn btn-success"> <span class="glyphicon glyphicon-hand-right"></span> Register </button>
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