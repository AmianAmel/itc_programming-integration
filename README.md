# itc_programming-integration
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sing In</title>
</head>

<style>
   
   body{
    background-repeat: no-repeat;
    background-attachment: fixed;
    backdrop-filter: blur(4px);

  
   }
    label{
        font-size: medium;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .h{
        font-size: large;
         text-align: center;
    }
    footer{
    width: 100%;
  height: 50px;
 color: rgb(243, 243, 96);
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
  padding-top: 30px;
  font-weight: 300;
 border-style:dashed;
font-size: x-large;
font-family: 'Courier New',
         Courier, monospace;

    
}

form{

position: relative;
padding: 60px 20px 30px 20px;
height: 900px;width: 480px; 
background-color: rgb(255, 220, 220,0.4);
border-radius: 30px;
-webkit-backdrop-filter: blur(15px);
backdrop-filter: blur(4px);
border:  3px solid rgb(255, 220, 220,0.4);
margin-left: 30%;
margin-top:70px;
  padding-top: 40px;

}
.check{
    margin-right: 14px;
    width: 14px;
}
.sub{width: 80px;
    height: 50px;
font-size: 15px;
font-weight: 500;
}
.input-box{
    width: 80%;
    height: 50PX;
    color: #040404;
    border: none;
    border-radius: 10PX;
padding: 7px 45px 0 20px;
background :rgba(224, 223, 223, 0.6);
font-size: 15px;
backdrop-filter: blur(2px);outline: none;
}
ul{ list-style: none;
  margin: 0;
  padding: 0;
}
ul li{

    display: inline-block;
  margin-right: 20px;
 
}
 li a {
  color: #ffffff;
  text-decoration: none;
  padding: 5px 10px;
  border-radius: 5px;
  font-family: 'Courier New',
         Courier, monospace;

}

</style>
<body  background=" photo1.jpg" style="height: 120vh;background-size: cover;">
    <footer><!------  LOGO +MENU-->
        <div style="display:flex; flex-wrap: wrap; cursor: pointer; ;">
         <img src="" style="width: 110px" alt="Logo" /><br>
        
 </div> 
   
     <ul><li><b  ><a href="page1.html">BACK TO HOME</a> </b></li>
     <li><b><a href="contact.html">CONTACT </a> </b></li></ul>  

      
 

     </footer>
   
   <!----register form--->
    <form action=""   method="get" style="align-content: center;"  >
      
        <div class="h" style="
        color: #292d32;font-family: 'Courier New',
         Courier, monospace;">
            <b >Sign In,Know</b><br>
            <label for="full-name" ></label><br>
        <small style="
        color: #292d32;font-family: 'Courier New', Courier, monospace;">
         We are happy to have you with us</small><br>
      
        </div><input type="text" name="name" class="input-box  " id="full-name"placeholder ="Full name"><br>
        <label for="full-name" ></label><br>
        <input type="email" name="email" id="adressmail" class="input-box"placeholder="Adress mail" ><br>
        <label for="full-name" ></label><br>
        <input type="tel" name="tel" class=" input-box" placeholder="Phone number" ><br>
    <label for=""></label>
        <!-----languages---->
        <medium style="color: #292d32;font-family: 'Courier New', Courier, monospace;"> <b> Choose a language(s)</b> </medium><br>
     <label for=""></label>
        <input type="checkbox" class="check">
        <label for="">English</label> 
        <input type="checkbox"  class="check">
        <label for="">Arabic</label>
        <input type="checkbox"  class="check">
        <label for="">Spanish</label>
        <input type="checkbox" class="check">
        <label for="">Frensh</label><br>
        <label ></label><br>
        <label for="" ></label><br>
        <medium style="color: #292d32;font-family: 'Courier New', Courier, monospace;">
             <b> Choose a Time</b> </medium><br>

        <!----timming--OF SUNDAY-->
        <input type="checkbox" name="time " class="check" > <label for="">SUNDAY</label> <br>
       
        <input type="checkbox" name="time " class="check" > 
        <label for="">10:30  TO 12:00 </label>
        <input type="checkbox" name="time " class="check" >
        <label for="">13:00 TO 14:30</label>
        <input type="checkbox" name="time " class="check">
        <label for="">18:00 TO 19:30</label><br>
        <label for=""></label><br>
        <!---TIMMING OF THURSDAY -->
            <input type="checkbox" name="time " class="check" ><label for="">THURSDAY</label><br>
            
            <input type="checkbox" name="time " class="check" > 
            <label for="">9:30  TO  11:00</label>
            <input type="checkbox" name="time " class="check">
            <label for="">13:00 TO 14:30</label>
            <input type="checkbox" name="time " class="check" >
            <label for=""> 17:15 TO 18:45</label><br>
             <label for=""></label><br>
             <!---TIMMING OF FRIDAY -->
             <input type="checkbox" name="time " class="check" > <label for="">FRIDAY</label><br> 
             <input type="checkbox" name="time " class="check" > 
             <label for="">9:30  TO  11:00</label>
             <input type="checkbox" name="time " class="check" >
             <label for="">13:00 TO 14:30</label>
             <input type="checkbox" name="time " class="check" >
             <label for=""> 17:15 TO 18:45</label><br>
             <label for="full-name" ></label><br>
             <label for="full-name" ></label><br>
       <input type="text" name="" id="" size="30"placeholder="how you see our services" class="input-box"><BR>
        <label for="full-name" ></label><br>
<input type="submit" value="SEND" class="sub">

    </form>

</body>
</html>
