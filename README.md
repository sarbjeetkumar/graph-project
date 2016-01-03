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
   
   ####For selection of enemys.
   
   	var enemiesTypes = {
		1:{
			speed:3,
			W: 38,   //height
		    H: 55,    //width
            //how many hits it will take to die 
		    health: 1,
		    score: 1, //how much score you get after killing this enemy
		    className: 'enemy1'   
		},
		2:{
			speed:5,
			W: 50,
		    H: 41,
		    health: 1,
		    score: 2,
		    className: 'enemy2'
		},
		3:{
			speed:5,
			W: 53,
		    H: 43,
		    health: 2,
		    score: 3,
		    className: 'enemy3'
		},
		4:{
			speed:7,
			W: 55,
		    H: 35,
		    health: 1,
		    score: 4,
		    className: 'enemy4'

This is for selection of enemys randomly and how they are defined and which speed they come and health means how many fires they will take to die and how much score they give .

####Things Left 

	function moveEnemy(enemy index){
    	//move the enemys 
	 //collision detecton 
	 //game over if collided 
        
	 }
    
    //funtion for fire 
    //key control 
    //space bar for fire 
    //up and down key for moving the ship .
    //game loop function
    
This is the four function left for this game to complete .
There is reference provided in the code from where i got the code.



