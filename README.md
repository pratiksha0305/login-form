#source code for login form using HTML and CSS.


<!doctype html>
<html>
 <head></head> 
 <body> 
  <div class="main"> 
   <h1>Login form</h1> 
   <br> 
   <br> 
   <br> 
   <br> 
   <div class="main1"> 
    <label>Email-Id:</label> 
    <input type="text" name="email id " placeholder="                        gmail.com"> 
   </div> 
   <br> 
   <br> 
   <div class="main2"> 
    <label>Password:</label> 
    <input type="password" name="password" placeholder=""> 
    <a href="#"><h6>Forget Password?</h6> </a> 
   </div> 
   <br> 
   <br> 
   <br> 
   <br> 
   <div class="main3"> 
    <button type="button" onclick="alert('Login successful')">Log in</button> 
    <br> 
    <br> 
    <br> 
    <hr> 
    <h5>Not a member?<a href="#">Sign up now</a></h5> 
   </div> 
  </div> 
 </body>
</html>



#css styling



body{
  
  background-image:url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSBCeSKBL7lvK-CX7ZVf7WWne_dgvXqKvf4Qg&usqp=CAU);
  background-repeat:no-repeat;
  background-size:cover;
  height:1850px;
}

div.main{
  background-image:url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcR6lvmcUXlhu_YjRAJRpcNIL16kunkDn-_UBg&usqp=CAU);
  
  width:800px;
  height:900px;
  background-position:center;
  background-size:cover;
  position:absolute;
  padding:10px;
  margin-left:80px;
  margin-top:400px;
  margin-bottom:150px;
  opacity:0.6;
   box-shadow:5px 10px;
  border-radius:20px;
  border-style:solid;
  border-width:5px;
}
h1{
  text-color:black;
  background-color:white;
  width:200px;
  height:30px;
   text-align:center;
   margin:auto;
   padding:20px;
   border-radius:40px;
  border-style:solid;
  border-width:5px;
  text-shadow:red;
  font-family:serif;
   box-shadow:5px 10px;
   
}

.main1{
  background-color:white;
  width:650px;
  height:600px;
  margin:auto;
  opacity:0.5;
  border-style:solid;
  border-radius:40px;
  
  text-color:black;
  background-color:white;
  width:550px;
 height:30px;
  
  margin:auto;
   padding:20px;
   border-radius:40px;
  border-style:solid;
  border-width:5px;
  font-size:30px;
  font-family:serif;
  
  
  }
  .main2{
    background-color:white;
  width:650px;
  height:600px;
  margin:auto;
  opacity:0.5;
  border-style:solid;
  border-radius:40px;
  
  text-color:black;
  background-color:white;
  width:550px;
   height:30px;
  /* text-align:center;*/
  /* margin:auto;*/
  padding:20px;
   border-radius:40px;
  border-style:solid;
  border-width:5px;
  font-size:30px;
    font-family:serif;
    
  }
  
  h2{
    font-size:30px;
    color:black;
    text-align:center;
    font-family:serif;
    
    
  }
  
  .main3 button{
font-size:30px;
font-family:serif;
padding:0px;
margin-left:315px;
text-align:center;
width:150px;
height:60px;
border-radius:40px; 
box-shadow:5px 10px;
border-style:solid;
        }
        
    
       h6{
      color:white;
      width:180px;
      height:20px;
       
      
     }
     
    h5{
      margin-left:120px;
      font-family:serif;
      font-size:20px;
      
    }
    input{
      outline:none;
      border:none;
      font-family:serif;
      font-size:30px;
    }
    input  [type=text]{  
      /*width:100%;*/
      display:inline-box;
      box-sizing:border-box;
      margin:auto;
      opacity:0;
       
    }
