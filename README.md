# PlaySCX

<html>

<head>
<title>
StarCraftX fanat game
</title>

<style>
a{
color:white;
outline: none;
  text-decoration: none;
  padding: 2px 1px 0;
  font-size: 1em;
}
a:hover{border-bottom: 1px solid;
  background: #cdfeaa;
color: darkblue;}


p{
	padding: auto;
	font-size: 3em;
    text-align: center;
    color: gray;
}

<!-- slider -->


.slider {
   width: 800px;
   height: 500px;
   overflow: hidden;
   border: 10px solid #000;
}

.middle {
   position: relative;
   top: 50%;
   left: 50%;
   transform: translate(-50%, -50%);
}

.navigation {
   position: absolute;
   bottom: 16px;
   left: 50%;
   transform: translateX(-50%);
   display: flex;
}

.bar {
   width: 30px;
   height: 8px;
   margin: 6px;
   cursor: pointer;
   background-color: #000;
   opacity: .5;
   border-radius: 10px;
   transition: all 0.4s ease;
}

.bar:hover {
   opacity: 1;
   transform:scale(1.1);
}

input[name="r"] {
   position: absolute;
   visibility: hidden;
}

.slides {
   width: 400%;
   height: 100%;
   display: flex;
}

.slide {
   width: 25%;
   transition: all 0.6s ease;
}

.img {
   width: 100%;
   height: 100%;
}

#r1:checked ~ .s1 {
   margin-left: 0;
}

#r2:checked ~ .s1 {
   margin-left: -25%;
}

#r3:checked ~ .s1 {
   margin-left: -50%;
}

#r4:checked ~ .s1 {
   margin-left: -75%;
}
</style>


</head>

<body bgcolor="black">


<div>
<img src="titledemo.png">
</div>

<div>
<p>
<a href="https://drive.google.com/drive/folders/18_XUSzPFyL2tL0LKItUpBtker0X0TdP1" target="_blank">Download</a></p>
</div>

<p>Screenshots</p>

<div class="slider middle">
   <div class="slides">
      <input type="radio" name="r" id="r1" checked>
      <input type="radio" name="r" id="r2">
      <input type="radio" name="r" id="r3">
      <input type="radio" name="r" id="r4">
      
      <div class="slide s1">
         <img src="4.png" alt="scx" class="img">
      </div>
      <div class="slide">
         <img src="6.png" alt="scx" class="img">
      </div>
      <div class="slide">
         <img src="7.png" alt="scx" class="img">
      </div>
      <div class="slide">
         <img src="9.png" alt="scx" class="img">
      </div>
   </div>
   <div class="navigation">
      <label for="r1" class="bar"></label>
      <label for="r2" class="bar"></label>
      <label for="r3" class="bar"></label>
      <label for="r4" class="bar"></label>
   </div>
</div>

<p>Contacts</p>

<p>
<a href="mailto:ezda.zvezda@gmail.com">e-mail</a>
</p>
<p>
<a href="https://github.com/ezdazvezda" target="_blank">GitHub</a>
</p>


</body>

</html>
