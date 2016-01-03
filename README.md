# graph-project
#####Game Name Sky wars 

This sky wars game is based on old sky ship game where you have to save your ship in the sky from another flying ships and you have to shot them to save and get the score .

####First i defined all my enemys in my css.

 
            /*Creating all the enemy's*/
            .enemy1{
                width: 38px;
                height: 55px;
                background-image: url(enemy1.png);
            }
            .enemy2{
                 width: 38px;
                height: 55px;
                background-image: url(enemy2.png);
            }
            .enemy3{
                 width: 58px;
                height: 50px;
                background-image: url(enemy3.png);
            }
            .enemy4{
                 width: 60px;
                height: 40px;
                background-image: url(enemy4.png);

Giving my enemys width and height 
and which enemy is that refrence to the image for eg - enemy1.png

####Defining the button and score and how many enemys are killed 

 <body>
        <div id="control">
		<div class="info">
             
			<div>hits:<span id="hits">0</span></div>
			<div>score:<span id="score">0</span></div>
		</div>
          
		<button id="restart">Restart</button>

        
    </body>
    
   To show how many enemys i have killed so far and if your game over then restart button to restart the game .



