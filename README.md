# <span style="color:red"> **Goal of this project** </span>
   The goal of this project is to simulate search and rescue operations by multiple agents within a relatively simple framework. 
   Collaborative and non-collaborative strategies will be tested and the performance of these strategies will be evaluated by Monte Carlo simulation. 



# <span style="color:red"> **Framework components** </span>

#### <span style="color:purple"> The field </span>
    An empty grid
    Can be any shape


#### <span style="color:purple"> The target  </span>
    Randomly placed on the grid at the beginning of each scenario (unless otherwise specified)
    Cannot move (unless otherwise specified)
    Can be detected by the robots within their detection range


#### <span style="color:purple"> The command center </span> : 
    Placed at (0,0) at the beginning of each scenario (unless otherwise specified)
    Cannot move (unless otherwise specified)
    Can receive message (ex : transmission of the target's position) from robots when they are close enough (transmission range)


#### <span style="color:purple"> Robots </span>: 
    Know their position on the grid
    Randomly placed on the grid at the beginning of each scenario
    Can move in of these 8 directions : "up", "down", "left", "right", "up right", "up left", "down right", "down left"
    Explore the site in search of the target while staying within the grid and avoiding collisions
    Can see the target when it is within their detection range
    Move towards the command center to transmit the target's position once they have found it
    Can communicate with each other and the command center within their transmission range
