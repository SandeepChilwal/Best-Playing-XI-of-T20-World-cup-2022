Problem Statement :
Elon Musk, the richest person of the world wants to make his cricket team for a t20 cricket league. He is ready to spend whatever amount is required to make the best t20 cricket team of the world. As we don’t know the strengths and weaknesses of the opponents, we need a team which can -

1) Score at least 180 runs on an average.
2) Defend 150 runs on an average.

Requirements :
1) Openers :
          Parameters                   Description                    Criteria

     Batting Average       Average runs scored in an inning          >30
     Strike Rate           Number of runs scored per 100 balls       >140
     Innings batted        Total innings batted                      >3
     Boundary %            % of runs scored in boundaries            >50
     Batting position      Order in which the batters played         <4


Anchors / Middle order:
                                                                              
       Parameters                   Description                    Criteria

     Batting Average       Average runs scored in an inning          >40
     Strike Rate           Number of runs scored per 100 balls       >125
     Innings batted        Total innings batted                      >3
     Avg. balls faced      Average balls faced in an inning          >20
     Batting position      Order in which the batters played         >2


Finisher / Lower order anchor:


       Parameters                   Description                    Criteria

     Batting Average       Average runs scored in an inning          >25
     Strike Rate           Number of runs scored per 100 balls       >130
     Innings batted        Total innings batted                      >3
     Avg. balls faced      Average balls faced in an inning          >12
     Batting position      Order in which the batters played         >4 
     Innings Bowled        Total innings bowled by the bowler        >1   


All rounders / Lower order:


       Parameters                   Description                    Criteria

     Batting Average       Average runs scored in an inning          >15
     Strike Rate           Number of runs scored per 100 balls       >140
     Innings batted        Total innings batted                      >2
     Batting position      Order in which the batters played         >4 
     Innings Bowled        Total innings bowled by the bowler        >2
     Bowling economy       Average runs allowed per over             <7
     Bowling strike rate   Avg no. of balls req to take wicket       <20 


Specialist fast bowlers:


       Parameters                   Description                    Criteria
 
     Innings Bowled        Total innings bowled by the bowler        >4
     Bowling economy       Average runs allowed per over             <7
     Bowling strike rate   Avg no. of balls req to take wicket       <16
     Bowling style         Bowling style of player                 ="%Fast%"
     Bowling average       No. of runs allowed per wicket            <20
     Dot Ball%             % dot balls bowled                        >40      
