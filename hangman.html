<!doctype>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<style>
.listclass{
  font-size:300%;
}
</style>
</head>
<body>
<h1>Hangman</h1>
<p>
<span>counter (head,neck,body,left hand,right hand,left leg,right leg):</span><span id = "counter"></span>
</p>
<p>
<span id="chosenWord"></span>
</p>
<p>
Used Letters:<span id="used"></span>
</p>
<p>Remaining:<span id="rem"></span></p>
<p id="blanks"></p>
<form>
  Enter Letter:<br>
  <input type="text" id = "guess" name="guess" maxlength="1" onkeyup="checkNum()">
 </form> 
  <button onclick="checkLetter()">Submit</button> <!--function doesnt work in <form> -->


<button  onclick="chooseWord()">New Game</button>
</body>


<script>
var allLetters = "";
var checkstart = false;
var words= ["cars","dragonfly","feelsbadman","chenggavin","dictionary","griefing"];
var pastLetters=[];
var selectedWord;
var remaining;
var count = 7;




function chooseWord(){
  count = 7;
  document.getElementById("counter").innerHTML = count;
  allLetters = "";
  document.getElementById("used").innerHTML ="";
  checkstart=true;
  $("#blanks > span").remove();
  pastLetters =[];
  count =7;
  index = Math.floor(Math.random() * (words.length));   
  selectedWord = words[index];
  remaining = selectedWord.length;
  document.getElementById("chosenWord").innerHTML=selectedWord;
  document.getElementById("rem").innerHTML=remaining;
  for(i=0;i<selectedWord.length;i++){
  	var letter = document.createElement("span");
    letter.id=i;
    letter.classList.add('listclass');
    var t = document.createTextNode("-");
    letter.appendChild(t);
    document.getElementById("blanks").appendChild(letter); 
  }
  return words[index];
}

function checkNum()
{

if (event.keyCode > 64 && event.keyCode <91 || event.keyCode == 8)
   return true;
else
   {
       alert("Please enter only lowercase letters");
       document.getElementById("guess").value="";
       return false;
   }
 
}


function checkLetter(){
	if(checkstart ==true){
		var used;
		var numcount = count;
		var userLetter = document.getElementById("guess").value;
		//is letter empty
		if(userLetter == ""){
			alert("You Entered Nothing!");
		}
		else{
			//check if used array is empty;
			if(pastLetters == []){
				pastLetters.push(userLetter);
				allLetters+= " ";
				allLetters+= userLetter;
			}
			//if used array not empty see if letter has been used yet
			else{
				for(i=0;i<pastLetters.length;i++){
					//letter already used
					if(pastLetters[i] == userLetter){
						alert("Letter Used Already");
						return;
					}
				}
				//if reached here we can add the new letter
				pastLetters.push(userLetter);
				allLetters+= " ";
				allLetters+= userLetter;
			}
			//lets see all the letters we guessed so far-left
			var match = false;
			document.getElementById("used").innerHTML = allLetters;
			//lets see if the letter is in the word
			var track=0;
			for(i=0;i<selectedWord.length;i++){
				if(selectedWord[i]==userLetter){
					document.getElementById(i).innerHTML=userLetter;
					match = true;
					track+=1;
				}
			}
			remaining-=track;
			document.getElementById("rem").innerHTML = remaining;
			if(match == false){
				count--;
				document.getElementById("counter").innerHTML = count;
				if(count == 0 && remaining > 0){
					chooseWord();
					alert("You Lose!");
					return;
					
				}
			}
			if(remaining == 0){
				alert("You Win!");
				chooseWord();
				return;
			}
			
		}
		
		
	}
	else{
		alert("Start A New Game!");
	}
	
}
</script>
</body>
<script></script>





</html>