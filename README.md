# CRIME-NAVIGATION-SYSTEM
it's a project through which user can register their complaints. Respective team will see concern and ill try to resolve it
[website1.zip](https://github.com/TechishGroup/CRIME-NAVIGATION-SYSTEM/files/7315129/website1.zip)




**ADMIN LOGIN**

<html>

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0"
<meta http-equiv="X-UA-Compatible" content="ie-edge">
<link rel="stylesheet" href="style.css">
<title>Document</title>

<style>
body{
    background-image: url('https://vivaldi.com/wp-content/themes/vivaldicom-theme/img/press/wallpapers/vivaldi-gradient-wallpaper.jpg');
    margin: 0;
     padding: 0;
    font-family: sans-serif;
    background-size: cover;
    }
.box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 400px;
    padding: 40px;
    background: rgba(0, 0, 0, 0.6);
    box-sizing: border-box; 
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5); 
    border-radius: 10px;
    }
.box h2{
    margin: 0 0 30px;
    padding: 0px;
    color: #fff ;   
    text-align: center;
}
.box .input-box {
        position: relative;
        color: #fff;
    }
.box .input-box input{
    width: 100%;
    padding: 10px 0px;
    font-size: 16px;
    color: #fff;
    letter-spacing: 1px;
    margin-bottom: 30px;
    border: none;
    outline: none;
    background: transparent;
    border-bottom: 1px solid #fff;
    }
.box.input-box label{ 
    position: absolute;
    top: 0;
    left: 0;
    letter-spacing: 1px;
    padding: 10px 0px;
    font-size: 16px;
}

.box.input-box input:focus label, 
.box .input-box input:valid label {
top: -18px;
left: 0px;
color: #03a9f4;
font-size: 12px;
}
.box input[type="submit"]{
background: transparent;
border: none;
outline: none;
color: #fff;
background: #227be3;
padding: 10px 20px;
border-radius: 5px;
cursor:pointer;
}

</style>

</head>
<body>
<div class="box">
<h2>Login</h2>
<form action="">
<div class="input-box">    
<input type="text">
<label for="">Username</label>
</div>
<div class="input-box">
<input type="password">
<label for="">Password</label>
</div>
<br>
<br>
<input type="submit">
</div>



</form>

</div>

</body>

</html>


**OFFICER LOGIN**


<html>

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0"
<meta http-equiv="X-UA-Compatible" content="ie-edge">
<link rel="stylesheet" href="style.css">
<title>Document</title>

<style>
body{
    background-image: url('https://vivaldi.com/wp-content/themes/vivaldicom-theme/img/press/wallpapers/vivaldi-gradient-wallpaper.jpg');
    margin: 0;
     padding: 0;
    font-family: sans-serif;
    background-size: cover;
    }
.box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 400px;
    padding: 40px;
    background: rgba(0, 0, 0, 0.6);
    box-sizing: border-box; 
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5); 
    border-radius: 10px;
    }
.box h2{
    margin: 0 0 30px;
    padding: 0px;
    color: #fff ;   
    text-align: center;
}
.box .input-box {
        position: relative;
        color: #fff;
    }
.box .input-box input{
    width: 100%;
    padding: 10px 0px;
    font-size: 16px;
    color: #fff;
    letter-spacing: 1px;
    margin-bottom: 30px;
    border: none;
    outline: none;
    background: transparent;
    border-bottom: 1px solid #fff;
    }
.box.input-box label{ 
    position: absolute;
    top: 0;
    left: 0;
    letter-spacing: 1px;
    padding: 10px 0px;
    font-size: 16px;
}

.box.input-box input:focus label, 
.box .input-box input:valid label {
top: -18px;
left: 0px;
color: #03a9f4;
font-size: 12px;
}
.box input[type="submit"]{
background: transparent;
border: none;
outline: none;
color: #fff;
background: #227be3;
padding: 10px 20px;
border-radius: 5px;
cursor:pointer;
}

</style>

</head>
<body>
<div class="box">
<h2>Login</h2>
<form action="">
<div class="input-box">    
<input type="text">
<label for="">Username</label>
</div>
<div class="input-box">
<input type="password">
<label for="">Password</label>
<br>
<br>
<form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="http://127.0.0.1:5500/officer%20office.html">
    <button type="submit">SUBMIT</button>
</form>

</body>

</html>


**ADD COMPLAINT**


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body{
  font-family: Calibri, Helvetica, sans-serif;
  background-color: rgb(0, 0, 0);
}
.container {
    padding: 50px;
  background-color: lightblue;
}

input[type=text], input[type=password], textarea {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
  background-color: rgb(255, 255, 255);
  outline: none;
}
 div {
            padding: 10px 0;
         }
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
.registerbtn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}
.registerbtn:hover {
  opacity: 1;
}
</style>
</head>
<body>
<form>
  <div class="container">
  <center><h1> -: COMPLAINT FORM :-</h1></center>
  <hr>
    <h1> COMPLAINANT DETAILS </h1>
<label> NAME OF COMPLAINANT: </label> 
<input type="text" name="NAME" placeholder= "NAME" size="15" required /> 
<label> PHONE/MOBILE </label> 
<input type="text" name="PHONE/MOBILE" placeholder="PHONE/MOBILE" size="15" required /> 
<label> EMAIL: </label>  
<input type="text" name="EMAIL" placeholder="EMAIL" size="15"required />
<label> ADDRESS: </label>  
<input type="text" name="ADDRESS" placeholder="ADDRESS" size="15"required />
<label> CITY: </label>  
<input type="text" name="CITY" placeholder="CITY" size="15"required />
<label> STATE: </label>  
<input type="text" name="STATE" placeholder="STATE" size="15"required />
<label> COUNTRY: </label>  
<input type="text" name="COUNTRY" placeholder="COUNTRY" size="15"required /> 


  <label> 
Gender :
</label><br>
<input type="radio" value="Male" name="gender"> Male 
<input type="radio" value="Female" name="gender"> Female 
<input type="radio" value="Other" name="gender"> Other


<hr>
    <h1> COMPLAINT AGAINST </h1>
<label> NAME OF PERSON: </label> 
<input type="text" name="NAME" placeholder= "NAME" size="15" required /> 
<label> PHONE/MOBILE </label> 
<input type="text" name="PHONE/MOBILE" placeholder="PHONE/MOBILE" size="15" required /> 
<label> ADDRESS: </label>  
<input type="text" name="ADDRESS" placeholder="ADDRESS" size="15"required />
<label> CITY: </label>  
<input type="text" name="CITY" placeholder="CITY" size="15"required />
<label> STATE: </label>  
<input type="text" name="STATE" placeholder="STATE" size="15"required />
<label> COUNTRY: </label>  
<input type="text" name="COUNTRY" placeholder="COUNTRY" size="15"required />


<hr>
    <h1> DETAILS OF COMPLAINT </h1>
<label> COMPLAINT DETAILS: </label> 
<input type="text" name="FULL DETAIL" placeholder= "FULL DETAIL" size="15" required /> 
<label> ADDRESS </label> 
<input type="text" name="ADDRESS" placeholder="ADDRESS" size="15" required /> 


</div>


  
<button type="submit" class="registerbtn">Register</button>    
</form>  
</body>  
</html>


**EMERGENCY PORTAL**
  

<html>

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0"
<meta http-equiv="X-UA-Compatible" content="ie-edge">
<link rel="stylesheet" href="style.css">
<title>Document</title>

<style>
body{
    background-image: url('https://www.ukecc.net/sites/default/files/Complaint%20letter.jpg');
    margin: 0;
     padding: 0;
    font-family: sans-serif;
    background-size: cover;
    }
.box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 1000px;
    padding: 100px;
    background: rgba(0, 0, 0, 0.6);
    box-sizing: border-box; 
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5); 
    border-radius: 10px;
    }
.box h2{
    margin: 0 0 30px;
    padding: 0px;
    color: #fff ;   
    text-align: center;
}
.box .input-box {
        position: relative;
        color: #fff;
    }
.box .input-box input{
    width: 100%;
    padding: 10px 0px;
    font-size: 16px;
    color: #fff;
    letter-spacing: 1px;
    margin-bottom: 30px;
    border: none;
    outline: none;
    background: transparent;
    border-bottom: 1px solid #fff;
    }
.box.input-box label{ 
    position: absolute;
    top: 0;
    left: 0;
    letter-spacing: 1px;
    padding: 10px 0px;
    font-size: 16px;
}

.box.input-box input:focus label, 
.box .input-box input:valid label {
top: -18px;
left: 0px;
color: #03a9f4;
font-size: 12px;
}
.box input[type="submit"]{
background: transparent;
border: none;
outline: none;
color: #fff;
background: #227be3;
padding: 10px 20px;
border-radius: 5px;
cursor:pointer;
}

</style>

</head>
<body>
<div class="box">
<h2>COMPLAINT HERE</h2>
<form action="">
<div class="input-box">    
<input type="text">
<label for="">Address</label>
</div>
<div class="input-box">
<input type="number">
<label for="">Mobile</label>
</div>
<br>
<br>
<input type="submit">
</div>



</form>

</div>

</body>

</html>


**ADMIN'S OFFICE**


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
    <title>ADMIN LOGIN</title>
    <title>Crime Navigation system</title>
    <style>
    body {
        background-image: url('https://images.freecreatives.com/wp-content/uploads/2016/01/Free-Solids-Background.jpg');
    }
    
    </style>
    <style>        
        .center {
          margin: 0;
          position: absolute;
          top: 50%;
          left: 50%;
          -ms-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
        }
        </style>
</head>

<body>
    <div class="center">
        <form method="get" class="inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="/">
            <button type="submit">OFFICERS DETAILS</button>
        </form>
        <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="/">
            <button type="submit">MANAGE OFFICERS</button>
        </form>
        <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="/">
          <button type="submit">SEE GRIEVANCE</button>
      </form>
</body>

</html>


**OFFICER'S LOGIN**


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
    <title>OFFICER LOGIN</title>
    <style>
    body {
        background-image: url('https://images.freecreatives.com/wp-content/uploads/2016/01/Free-Solids-Background.jpg');
    }
    
    </style>
    <style>        
        .center {
          margin: 0;
          position: absolute;
          top: 50%;
          left: 50%;
          -ms-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
        }
        </style>
</head>

<body>
    <div class="center">
        <form method="get" class="inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="/">
            <button type="submit">VIEW COMPLAINT</button>
        </form>
        <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="/">
            <button type="submit">UPDATE CASES</button>
        </form>
</body>

</html>


**SHOW & SAVE PASSWORD FEATURE**


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
  <title>Admin Login</title>
  <style>
    body {
        background-image: url('https://lh3.googleusercontent.com/XePhpEPcJqi-biBWFbhqM9Xv9ViXx_hW0XBiEMnP-6e0vDZK-XlhI2DmlXUoarLwjkDztiSW8pX9ovPweRDUjZ1cr3a-TstRT6mSrascu2rJTUe2zQbFTjg3ovdb5o_w8nrgjarRATSpCYu3Ne94csGoC0ElGRvzXosxyozSwZvBA5odN5dyeJwqcwMhTyQtdEx0L52dVizjtOMm_9l9d1-Tc8ZVj6UX97v7E54hmb8jN4rngepIrvbjfDYnOzlXrFGWFErkv1vjk39xECIW6V8mQFTwUlIlCwkX0nU_eBmHQSH4cPxED-zuN5OX6o1s6fR1C1Q61rXZHJHdAWhURNqBr2dcDaIIpPrkPo-snbJvT3seM0pjWJt9WPiCKoSwgWGlF5ey-NzmZW-7IKIH-RKWkdM4Tx9k8s8bFvwSPkqwzyARCqhqRcRszAOVBKac-LgrXLT4i1LJaTrBoVAI7vR7vpbq-ygLcm9X9DqdqS3cx1vmojSerOhUdzBkxH45ecrZERIcPjx69p7TwSoyBKq-LBNsDlagkuSm0h7bsPN0WchxDYC0fEcnwG9xc52yInycVHfXpoDQMyeMi9tbxd_o4PX_pay2ZygBcMhZkqzFgIBkhMNnzslBh0OJ7a7YEdnZsvEW0cnJhKNBNkUspXeyNgyhT1nOBInCUedhJxQknSg1kfIl97tnvlAPZPW9nIiGM95o55NefvQdUX3va2kB=w1366-h618-no?authuser=0');
    }
    
    </style>
</head>
<body>
  <nav class="md:ml-auto md:mr-auto flex flex-wrap items-center text-black justify-center">
    <a href="http://127.0.0.1:5500/index.html" class="mr-5 hover:text-gray-900">Home</a>
    <a href="http://127.0.0.1:5500/about.html" class="mr-5 hover:text-gray-900">About</a>
    <a href="http://127.0.0.1:5500/contact.html" class="mr-5 hover:text-gray-900">Contact Us</a>
  </nav>
  
  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-12">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900"></h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base"></p>
      </div>
      <div class="flex lg:w-2/3 w-full sm:flex-row flex-col mx-auto px-8 sm:space-x-4 sm:space-y-0 space-y-4 sm:px-0 items-end">
        <div class="relative flex-grow w-full">
          <label for="full-name" class="leading-7 text-sm text-gray-600">ID</label>
          <input type="text" id="full-name" name="full-name" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-black py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
        </div>
        <div class="relative flex-grow w-full">
          <label for="email" class="leading-7 text-sm text-gray-600">Password</label>
          

          
          <input type="password"  id="myInput"  name="Password" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-black py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"><br><br>
          <input type="checkbox" onclick="myFunction()">Show Password
          
          <script>
          function myFunction() {
            var x = document.getElementById("myInput");
            if (x.type === "password") {
              x.type = "text";
            } else {
              x.type = "password";
            }
          }
          </script>
       
       
       
       
       
        </div>
        <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-white rounded text-lg" action="/">
          <button type="submit">Login</button>
      </form>
      </div>
    </div>
  </section>
</body>
</html>



**Automatic Slideshow FEATURE**
    
    
    <!DOCTYPE html>
<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/w3css/3/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
<body>

<!-- Slide Show -->
<section>
  <img class="mySlides" src="https://lifebeyondnumbers.com/wp-content/uploads/2019/01/National-Emblem-of-India.jpg"
  style="width:100%">
  <img class="mySlides" src="https://mcmscache.epapr.in/post_images/website_350/post_18389809/full.jpg"
  style="width:100%">
  <img class="mySlides" src="https://images.indianexpress.com/2018/06/red-fort-759-getty-images.jpg"
  style="width:100%">
</section>
<script>
// Automatic Slideshow - change image every 3 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 3000);
}
</script>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
    <title>Crime Navigation system</title>
    <style>
    body { }
    
    </style>
    <style>        
        .center {
          margin: 0;
          position: absolute;
          top: 50%;
          left: 50%;
          -ms-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
        }
        </style>
</head>

<body>
    <header class="text-gray-600 body-font">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
            <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
                
                <span class="ml-3 text-xl">CRIME NAVIGATION SYSTEM</span>
            </a>
            <nav class="md:ml-auto md:mr-auto flex flex-wrap items-center text-black justify-center">
                <a href="http://127.0.0.1:5500/index.html" class="mr-5 hover:text-gray-900">Home</a>
                <a href="http://127.0.0.1:5500/about.html" class="mr-5 hover:text-gray-900">About</a>
                <a href="http://127.0.0.1:5500/contact.html" class="mr-5 hover:text-gray-900">Contact Us</a>
            </nav>
                <form method="get" class="inline-flex items-center bg-blue-200 border-black-200 py-1 px-4 focus:outline-black hover:bg-white-200 rounded text-base mt-4 md:mt-0" action="http://127.0.0.1:5500/emergency%20complain.html">
                    <button type="submit">Emergency Portal</button>
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                class="w-4 h-4 ml-1" viewBox="0 0 24 24">
                <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
            </form>
            </button>
        </div>
    </header>
    <section class="text-gray-600 body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
          <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
            <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">
              <br class="hidden lg:inline-block">
            </h1>
            <div class="center">
                <form method="get" class="inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="http://127.0.0.1:5500/Admin%20Login.html">
                    <button type="submit">Admin Login</button>
                </form>
                <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="http://127.0.0.1:5500/officer%20login.html">
                    <button type="submit">Officer Login</button>
                </form>
                <form method="get" class="ml-4 inline-flex text-black background-color:#e7e7e7 border-0 py-2 px-6 focus:outline-none bg-gray-200 rounded text-lg" action="http://127.0.0.1:5500/Complaint%20Form.html">
                    <button type="submit">Add Complaint</button>
                </form>
            </div>
          </div>
        </div>
      </section>
</body>

</body>
</html>


