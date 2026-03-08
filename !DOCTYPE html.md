<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<title>For My Begum ❤️</title>  
  
<style>  
body{  
    margin:0;  
    font-family:Arial;  
    background:linear-gradient(135deg,#ff9a9e,#fad0c4);  
    display:flex;  
    justify-content:center;  
    align-items:center;  
    height:100vh;  
}  
  
.envelope{  
    width:200px;  
    height:120px;  
    background:white;  
    position:relative;  
    cursor:pointer;  
    box-shadow:0 10px 25px rgba(0,0,0,0.2);  
}  
  
.envelope:before{  
    content:"";  
    position:absolute;  
    top:-60px;  
    left:0;  
    border-left:100px solid transparent;  
    border-right:100px solid transparent;  
    border-bottom:60px solid white;  
}  
  
.message{  
    display:none;  
    max-width:600px;  
    background:white;  
    padding:30px;  
    border-radius:15px;  
    box-shadow:0 15px 35px rgba(0,0,0,0.2);  
    overflow:auto;  
    height:70vh;  
}  
  
h2{  
text-align:center;  
}  
  
</style>  
</head>  
  
<body>  
  
<div class="envelope" onclick="openEnvelope()"></div>  
  
<div class="message" id="msg">  
<h2>For My Begumm ❤️</h2>  
  
<p>  
Mere ladlyyyyy future begummmm<br><br>  
  
Ma jane se pehle ye kahna chahta k<br><br>  
  
I promise that k nikah k bad tm ne jasa Socha hua hm wase h life guzre g<br>  
Blkay us se b kahin gunah zayda axhe<br>  
Ma gurente deta k hmre life same wase h ho g jasa tm chahti jasa hm dono ne mil kr socha hua ❤️<br><br>  
  
Jasa tm ne muje call pr bataya thaaaaaaa bilkul wasaaa hiiiii<br>  
Jasa tm chahti ek ghr ho us ma srf ma or tm<br>  
Hm mil kr cooking krein<br>  
Ma talwat kru or mere shoulder pr tmra sr<br>  
Bilkul asa he ho ga begum<br>  
I promise 🤍<br><br>  
  
Ma talwat pr ke sunao ga tm mere shoulder pr sr rkna 🤍<br>  
Dherrr sare batein krein ge hr topic k relatedd<br>  
Kabheeee ma bolo gaaa tm sunaaa<br>  
Kabhe tm bolna ma suno gaaaa<br><br>  
  
Sameeeee dressing krein g jaha b jain ge<br>  
Tme khd apne hatho se kana kilaua kro ga<br>  
Tme khd apne hato se mehndi lagaya kro gaa<br>  
Apne hatho se tmre hatho ma churian pehnaya kru ga ❤️<br>  
Khd tme rings pehnaya kro ga apne se 🤍<br><br>  
  
Tmre balo pr brush b ma h kia kru ga 🫠❤️<br>  
Hr chzzz hm mil kr krein h<br><br>  
  
Bs ma itna kahna chahta jasa tm chahti hm waseeee h life gusre g mere ladlyyyy begummmmm 🤍<br>  
Tmra hathh kabhii ni chorne wala<br>  
Ekele ma bi nahi or na h sb k smne 🤍<br><br>  
  
Begummmm ma tm se behadd pyar krta<br>  
Khd se b zaydaaaaaaaaaaaaaaa<br>  
Maaaa srfff tmraaaaa huuuuuuu<br>  
SRF TMAAAHARAAAA<br><br>  
  
I will really missss uhh alotttt Begummmmmm 🫠❤️<br>  
And I will alwaysssss love uhhhh the way uh want 🫠🤍<br>  
Loveeeee uh alottt begummm 🤍  
</p>  
  
</div>  
  
<script>  
  
function openEnvelope(){  
  
let pass1 = prompt("Enter password to open the letter");  
  
if(pass1 === "zanoor"){  
  
let pass2 = prompt("Enter second password");  
  
if(pass2 === "Mere ladlyyyyy future begummmm"){  
  
document.querySelector(".envelope").style.display="none";  
document.getElementById("msg").style.display="block";  
  
}else{  
alert("Wrong second password");  
}  
  
}else{  
alert("Wrong password");  
}  
  
}  
  
</script>  
  
</body>  
</html>  
