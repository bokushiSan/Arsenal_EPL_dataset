# Arsenal_EPL_dataset

Dataset of Arsenal matches and player statistics from 2017/18 season until 28.02.2023.

### Context

Ever since I started working with data, I've always wanted to break down the statistics of my favorite football club, Arsenal FC. So, I put together this dataset so that you too can dive into the world of football and the world of Arsenal in particular.

### Content

This dataset includes **214** results of Arsenal FC matches starting from 2017/18 season up to 28.02.2022, **2741** record of every player, who played in these matches with advanced statistics and **218** records of every goalkeeper.

`players.csv` includes the following columns:

-   `LastName` - Player's last name
-   `FirstName` - Player's first name
-   `Date` - Match date
-   `Start` - Starting lineup (1 - in start, 0 - from bench)
-   `Pos` - Position
-   `Min` - Minutes played
-   `G` - Goals
-   `A` - Assists
-   `PK` - Penalty kicks made
-   `PKA` - Penalty kicks attempted
-   `S` - Total shots
-   `SoT` - Shots on target
-   `Touches` - Total touches
-   `Tackles` - Total tackles
-   `Ints` - Interceptions
-   `Blocks` - Blocks
-   `xG` - Expected goals
-   `npxG` - Expected non-penalty goals
-   `xAG` - Expected assists
-   `Passes` - Total passes
-   `PassesA` - Attempted passes
-   `PrgPas` - Progressive passes
-   `Carries` - Number of times player controlled the ball
-   `PrgCar` - Progressive carries
-   `Line` - Line (forward, midfielder, defender)
-   `C` - Squad's captain

`goalkeepers.csv` includes the following columns:

-   `LastName` - Goalkeeper's last name
-   `FirstName` - Goalkeeper's first name
-   `Date` - Match date
-   `Start` - Starting lineup (1 - in start, 0 - from bench)
-   `Pos` - Position
-   `Min` - Minutes played
-   `SoTA` - Shots on target against
-   `GA` - Goals against
-   `Saves` - Total saves
-   `PSxG` - Post-shot expected goals
-   `PKatt` - Penalty kick attempted
-   `PKA` - Penalty kick allowed
-   `PKm` - Penalty kick missed
-   `PassAtt` - Passes attempted
-   `Throws` - Throws attempted
-   `AvgLen` - Average pass length (in yards)
-   `GKAtt` - Goal kicks attempted
-   `GKAvgLen` - Average goal kick length (in yards)
-   `C` - Squad's captain

`matches.csv` includes the following columns:

-   `Season` - Season
-   `Tour` - Matchweek
-   `Date` - Date of the match
-   `Time` - Time of the match
-   `Opponent` - Opponent team
-   `HoAw` - Arsenal's home/away
-   `ArsenalScore` - Arsenal goals
-   `OpponentScore` - Arsenal's opponent goals
-   `Stadium` - Match stadium
-   `Attendance` - Match attendance
-   `Coach` - Arsenal's head coach
-   `Referee` - Referee of the match

### Notes

This dataset will be updated with new matches as well as for past seasons.
COYG!

### Acknowledgements

The data is gathered from several sources including transfermarkt, flashscore and fbref.com.

### Author

Rustem "bokushi" N.
Ufa, Russian Federation
