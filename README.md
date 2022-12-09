# UMS
umiversity management portal
index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UMS Login</title>
    <link rel="stylesheet" href="/Login Page/Web projects/style.css">
</head>
<body>
    <span id="logo"><img src="lpu_logo.webp" alt="LPU"></span>


    <div id="lpu_text1" class="text">UMS</div>

    <div id="lpu_text2" class="text">University Management System</div>

    


    <main>
        <div id="form" class="form" >
            <form action="">
                <div > Sign In</div>
                <hr style="color: white;">

                <input type="number" name="reg" maxlength="8" placeholder=" User ID" required >
    
                
                <input type="password" name="pass" autocomplete="current-password" placeholder=" Password" required >
                
                <select name="dropdownlist" id="list" aria-placeholder="Your Branch">
                    <option value="">Your Branch</option>
                    <option value="">Chhattisgarh</option>
                    <option value="">Bihar</option>
                    <option value="">Andhra Pradesh</option>
                    <option value="">Uttar Pradesh</option>
                </select>
                    
                <button type="submit" ><a href="/Main Page/index.html" style="color:white;text-decoration: none;">Login</a></button>
                
            </form>
        </div>
    </main>
    <section id="ontap_button">
        <button type="submit" id="forget_password">forget UMS <br> Password</button>
        <button type="submit" id="student_mall">Staff <br>mall</button>
        <button type="submit" id="staff_mall">Student <br>mall</button>
    </section>
    <div id="icon_descp"><pre>Download Our Official App</pre></div>
    <div id="icon" >
        <a class="icon1" href="https://itunes.apple.com/in/app/lputouch/id509819753?mt=8" target="_blank">
            <img src="https://ums.lpu.in/lpuums/login_images/apple_icon.png" alt="IOS">
        </a>
        <a class="icon2" href="https://play.google.com/store/apps/details?id=ums.lovely.university">
            <img src="https://ums.lpu.in/lpuums/login_images/android_icon.png" alt="Android">
        </a>
    </div>
    <footer></footer>
</body>

</html>
style

body{
    background-image:url(bg.jpg);
    background-repeat:no-repeat;
    background-size: cover;
    background-attachment: fixed;
  
}
 
#logo{
    display: flex;
    justify-content: center;
    width: auto;
    margin-top: 50px;
    
}
.text{
    display:flex;
    justify-content:center;
    background-color:none;
    font-weight: 700;
    font-family: sans-serif;
}
#lpu_text1{
    font-size: 70px;
    color: white;
    text-shadow: -2px 6px 1px black;
}
#lpu_text2{
    font-size: 35px;
    color:white;
    text-shadow: 3px 2px 4px black;
    
    margin-left: 350px;
    margin-right: 350px;
    border-radius: 10px;
    padding:5px;
    box-shadow: 0px 2px 2px black;
}

form div span{
    background-color: orangered;
}
form div{
    font-size: 40px;
    padding-left: 20px;
    font-weight:900;
    font-family:'Times New Roman', Times, serif;
    color: rgb(255, 55, 0);
    text-shadow: 1px 1px 3px black;
}
#form{
    background-color: rgba(0, 0, 0,0.4 );
    height: 230px;
    width: 500px;
    border: 3px solid white;
    align-items: center;
    border-radius: 4px;
    box-shadow: 2px 2px 3px black;
    margin: 100px auto;
    margin-top: 10px;
    margin-bottom: 0px;
}

form input,form select{
    border:solid 1px rgb(0, 0, 0);
    border-radius: 2px;
    margin:10px 10px;
    padding: 0px;
    outline:none;
    font-size: 15px;
    background-color: aliceblue;
}
form select{
    height: 28px;
    width: 195px;
    height: 30px;
    margin-left: 30px;


}
form input{
    padding: 5px;
    margin-left: 30px;
}
form input::after{
    border:solid black;
}


form button{
    background-color:rgb(255, 55, 0);
    color: white;
    font-size: 15px;
    cursor: pointer;
    outline:none;
    margin: 10px auto 0px auto;
    font-weight: 500;
    height: 50px;
    width: 50px;
    display: block;
    border: 1px black;
    border-radius:50%;
    box-shadow: 1px 1px 4px black;
    text-shadow: 0 0 3px black;
}
body section{
    display: flex;
    margin-left:34%;
    color: white;
    font-size: 15px;
}

body #forget_password{
    margin-right: 200px;
    cursor: pointer;
    background-color: green;
}
#student_mall{
    margin-left: 135px;
    background-color: green;
}
#staff_mall{
    margin-left: -15px;
    background-color: blueviolet;
}

section button{
    border:none;
    color: white;
    font-size: 8px;
    margin-top: 3px;
    width: 60px;
    height:28px;
    background-color:orangered;
    border-bottom-left-radius:100px;
    border-bottom-right-radius:100px;
    cursor: pointer;
    box-shadow: 1px 1px 2px black;
}
#icon_descp{
    padding-top: 90px;
    display: block;
    text-align: center;
    
    color: rgb(255, 255, 255);
    text-shadow:1px 1px 1px black;
    font-size: 20px;
    font-weight: 600;
}
#icon{
    display:flex;
    justify-content: center;
}
style att
#cards2{
    height: 400px;
    margin-left: 10%;
    margin-top: 20px;
    align-items: center;
    align-content: center;
    display: grid;
    column-gap: 30px;
    grid-template-columns: 725px auto;
}
#cards2 #card1{
    border: 1.5px solid rgb(255, 179, 37);
    height: 400px ;
    width: 700px;
    border-radius: 10px;
    box-shadow: 10px -10px 50px rgba(0, 0, 0,0.4);
}
#cards2 #card2{
    border: 1.5px solid rgb(255, 179, 37);
    height: 400px ;
    width: 300px;
    border-radius: 10px;
    box-shadow: 10px -10px 50px rgba(0, 0, 0,0.4);
}
#cards2 legend{
    background-color: rgb(255, 143, 52);
    color: white;
    font-size: 15px;
    font-weight: bolder;
    padding:8px 30px 8px 30px;
    border: 1px solid rgb(255, 179, 37);
    border-radius: 4px;
    border-radius: 30px;
    letter-spacing: 2px;
}
#cards2 img{
    height: 320px;
    width: 650px;
    margin: 0; 
    display: block;
    margin-left: auto;
    margin-right: auto;
}
#card2 img{
    height: 320px;
    width: 290px;
}
#card2 section{
    background-color: rgb(41,121,191);
    border-radius: 10px;
    color: rgb(255, 255, 255);
    align-items: center;
    align-content: center;
    margin-left: 70%;
    padding: 3px;
    padding-left: 8px;
    font-size: 15px;
    cursor: pointer;
}
#cards2 #attendence{
    display: grid;
    column-gap: 60%;
    grid-template-columns: auto auto;

}
#cards2 span{
    font-size: 20px;
    color: rgb(41,121,191);
}

style placements
heading2_placement {
    font-weight: border;
    font-size: 40px;
    margin-left: 150px;
    border-bottom: 1px solid black;
}

#cards3 {
    height: 400px;
    margin-left: 10%;
    margin-top: 20px;
    align-items: center;
    align-content: center;
    display: grid;
    column-gap: 30px;
    grid-template-columns: 370px auto;
}

#cards3 #card1 {
    border: 1.5px solid rgb(255, 179, 37);
    height: 300px;
    width: 350px;
    border-radius: 10px;
    box-shadow: 10px -10px 50px rgba(0, 0, 0, 0.4);
}

#cards3 #card2 {
    border: 1.5px solid rgb(255, 179, 37);
    height: 300px;
    width: 200px;
    border-radius: 10px;
    box-shadow: 10px -10px 50px rgba(0, 0, 0, 0.4);
}

#cards3 legend {
    background-color: rgb(255, 143, 52);
    color: white;
    font-size: 15px;
    font-weight: bolder;
    padding: 8px 30px 8px 30px;
    border: 1px solid rgb(255, 179, 37);
    border-radius: 4px;
    border-radius: 30px;
    letter-spacing: 2px;
}
#cards3 #card1 img{
    height:200px;
    width: 350px;
}
#cards3 #card2 img{
    margin: 0%;
    height: 200px;
    width: 650px;
}
