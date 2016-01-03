# graph-project
#####created for my graphics project 

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
              <!--for score and how many hits -->
			<div>hits:<span id="hits">0</span></div>
			<div>score:<span id="score">0</span></div>
		</div>
          <!--For button to restart -->
		<button id="restart">Restart</button>
	</div>
	<div id="game-wrap">
		<div id="ship"></div>
		<div id="bg">
			<div></div>
			<div></div>
		</div>
		<div id="statistic"></div>
	</div>
        
    </body>
    
    




