# DungeonsandDragons.github.io
my website
<html>
 <head>
  <title> Dungeons and Dragons</title> 

<style>
   .navmenu{
text-align:center;
     color:white;
     background-color:red;
   }
   .navitems{
list-style-type:none;
     display:inline;
     margin-right:5px;
     padding:2px 5px;
   }
  </style>
 </head>
 <body>
  <nav>
   <ul class="navmenu">
  	<li class="navitems">Home</li>
   	<li class="navitems">Photos/Videos</li>
   	<li class="navitems">Resources</li>
   	<li class="navitems">Coming Soon!</li>
   </ul>
  </nav>

 </head>
 <body style="border:5px double red;padding:10px">
	 <h1>What is Dungeons and Dragons?</h1>

	 <h3>D&D is the worlds greatest roleplaying game.</h3>

	 <p style="color:red">
	 	How to play D&D
	 </p>
	 
	 <h3>The Dungeon Master describes the environment and the players respond with how their characters react. It's that simple!</h3>




	 <h3>All you need to play is some dice, a writing utensil, paper, and your imagination!</h3>


<img src="https://cdn.discordapp.com/attachments/677577788060073990/678963011540746240/PHB---Tyler-Jacobson.jpg" />
<small>Image Credit: Tyler Jacobson</small>

<h3>Who invented D&D?</h3>
  	<form>
      <input type="radio" name="trivia" value="Gary Gygax"> Gary Gygax<br>
      <input type="radio" name="trivia" value="Dave Arnesson"> Dave Arnesson<br>
      <input type="radio" name="maple" value="Huh?"> Huh?<br>
      <input type="button" value="Click Here" onclick="run()">
      <div id="response"></div>
    </form>
  </body>
  <script>	
  function run(){
  	var r = document.getElementsByName("trivia");
  	var e = document.getElementById("response");
  	for(var i=0; i <r.length; i++){
  		if(r[i].checked == true && r[i].value == "Gary Gygax"){
  			e.innerHTML = "Natural 20!!!";
  			return;
  		} else {
        	e.innerHTML = "Critical failure!!!";
        }
  	}
  }
  </script>

  <a href="https://simplycoding.org/code-dungeon"></a>

  <audio width="400" height="220" controls>
   <source src="file:///C:/Users/Owner/Downloads/twenty%20one%20pilots%20-%20Levitate%20(Official%20Video).mp3" type="audio/mpeg">
   </audio>

<head>
 	<style>
.box{
 			display:inline-block;
 			width: 100px;
 			height:100px;
 			background-color: white ;
 		}

 		.image{
 			border:5px solid green;
 		}
 	</style>
 </head>
 <body>
 	<div class="box"></div>
 	<img class="image" width="25%" src="https://cdn.discordapp.com/attachments/677577788060073990/678978404027990016/9k.png" />

<iframe width="1134" height="638" src="https://www.youtube.com/embed/On3UNCnBnWg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
<blockquote class="reddit-card" data-card-created="1581951777"><a href="https://www.reddit.com/r/dndmemes/comments/f52rb7/were_making_our_cat_into_a_character_so_of_course/">We're making our cat into a character, so of course it's only fair we let her roll her own stats.</a> from <a href="http://www.reddit.com/r/dndmemes">r/dndmemes</a></blockquote>
<script async src="//embed.redditmedia.com/widgets/platform.js" charset="UTF-8"></script>

<img class="image" width="25%" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSHd9Df_tOafzU8wDtAoKrMyLhH_zD6FnjJvp82wHXeFEUsg7UO">

<head>
  <script>
   function c(){
    var count = 0;
    var sen = "It's time to roll initiative";
    var letter = "i";
    for(var i = 0; i < sen.length; i++){
     if(sen[i] == letter){
      count++
     }
    }
    alert("Hello. Welcome to my website! It's time to roll initiative!");
   }
  </script>
 </head>
 <body onload="c()"></body>
 


 </body>
</html>
