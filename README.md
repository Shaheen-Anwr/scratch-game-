# Space Exploration (Scratch)

#### Video Demo: <URL HERE>

#### Description:
A space exploration game built in Scratch where the player pilots a `Rocketship` sprite across space to visit target planets (`Earth` and `Planet2`). Starting from a base position, the player steers and propels the rocketship toward planets, triggering arrival feedback, resetting back to the starting point, and incrementing a counter that tracks how many planets have been visited.

#### Controls:
- **Left Arrow**: Rotate the rocketship counterclockwise.
- **Right Arrow**: Rotate the rocketship clockwise.
- **Up Arrow**: Move the rocketship forward.
- **Green Flag**: Reset the `planetsVisited` counter and initialize the rocketship's starting position and state.

#### Technical Highlights:
- **Sprites**: Uses multiple non-cat sprites (`Rocketship`, `Earth`, and `Planet2`) on a space backdrop.
- **Scripts**: Organizes behavior across multiple independent scripts, including startup/movement control, continuous collision detection, and a custom block definition.
- **Conditionals & Loops**: Uses `forever` loops along with `if` conditionals to handle real-time keyboard steering and planet touch detection.
- **Variables**: Uses the `planetsVisited` variable to reset on game start and increment whenever a planet is visited.
- **Custom Block with Parameter**: Defines `visitPlanet (planetName)` taking `planetName` as an input parameter to display an arrival message, increment `planetsVisited`, and return the rocketship to its starting coordinates.
# scratch-game-
