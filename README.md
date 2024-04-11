# <span style="color:red"> **Framework components** </span>

The field 

An empty grid
Can be any shape
add Codeadd Markdown
The target 

Randomly placed on the grid at the beginning of each scenario (unless otherwise specified)
Cannot move (unless otherwise specified)
Can be detected by the robots within their detection range
add Codeadd Markdown
The command center :

Placed at (0,0) at the beginning of each scenario (unless otherwise specified)
Cannot move (unless otherwise specified)
Can receive message (ex : transmission of the target's position) from robots when they are close enough (transmission range)
add Codeadd Markdown
Robots :

Know their position on the grid
Randomly placed on the grid at the beginning of each scenario
Can move in of these 8 directions : "up", "down", "left", "right", "up right", "up left", "down right", "down left"
Explore the site in search of the target while staying within the grid and avoiding collisions
Can see the target when it is within their detection range
Move towards the command center to transmit the target's position once they have found it
Can communicate with each other and the command center within their transmission range
