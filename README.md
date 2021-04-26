# AssemblyProject
CSC258H5S Winter 2021 Assembly Programming Project  
Khadeeja Naseer and Anna Liang
Doodle Jump: MARS Adventure  
    
   Instructions:  
   While listening in on a radio transmission from a human spaceship, the alien  
   heard about Elon Musk and his great interest in Mars. It wondered what  
   treasures could be found there, and took it upon itself to race against Musk. So  
   it's journey began...  
  
   Help the alien hop to Mars! Move left and right to position the alien so that  
   it can land safely on a platform (the blue lines). The alien will fall if you miss.   
   If you can't land on a platform before it falls to the edge of the screen,   
   then the poor alien will have to restart :(  
  
   One man's trash is another's treasure. Help the alien collect golden meteorites to   
   boost its morale. It will move faster and your score will double!  
      
   Controls:  
   j: move left one unit  
   k: move right one unit  
   * Note: try not to spam or press too many keys at once or MARS will crash.  

   BONUS FEATURES  
 1. Background music plays throughout during the game. Moreover, there  
    are sound effects played when the alien lands on a platform and when  
    the alien fails its mission.  
 2. Score is constantly updated and displayed on screen, and remains   
    displayed on the game-over screen.  
 3. Difficulty increases with respect to score. As the score increases,   
    the sleep amount decreases, making the game run faster.   
    Speficically, everytime score increases by 14, sleep amount drops by  
    1 ms. (this can be adjusted, but we made the score increase requirement  
    smaller so that speeds increase sooner for easier testing)  
    Once sleep amount reaches 25 ms, the game will be running quite quickly  
    so difficulty does not increase any further.  
 4. Power-up for the alien to collect; doubles the score upon collection.  
