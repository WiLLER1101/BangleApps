# Badminton Scorekeeper
###### WiLLER

# Overview
Badminton Scorekeeper is designed to help badminton players to keep track of scores during game.

Didn't spend too much time on it, just to make it works before my game with friends in weekend.

# Feature
- **Score Tracking**
  - Simply tap to scores for both teams, with Deuce rule logic included.
  - Serving player indication added, we always forgot who was standing on left side in last score.
  - Undo button added, used when input score for the wrong team (well, hopefully one day I can even have a Challenge mode in sport center...)
  - Customized player name list, if you install language pack I think it supports other language like Japanese, Chinese, etc. (but don't make the name too long)
  - Always On Display during game. Just noticed that everytime clicking the button to unlock the screen to add score during a game is uncomfortable.

# Limitations
- **Lack of configuration like disbling deuce, single match, BO3**: Well, these are not common in my use case, so I didn't made that part...For 1V1, you can just...select same player on one side(?
- **Not support exporting Match Result**: Actually I can do this part, like export the match result score into csv, but I am not sure how to visualize it or **make use of** this data. Maybe after I work on the html page first?
- **"Hey WiLLER your code sucks"**: Sorry for the shitty code, I do lack of experience. Would be glad if you may suggest any improvements on coding part.

# Usage
1. Prepare for new Game:
   - Open the app and press start.
   - Select 4 players and click next.
   - Click on the badminton icon to toggle (which team serves first). Swapping player position by clicking the arrow icons between players. When everything is ready, you may start the game.
2. Score:
   - Click on the side of teams to score. Player area marked in red indicates that player serves.
   - Game over when one team scores 21(not in deuce situation) or one team leads 2 score(in deuce situation)
  
# Pending
- HTML page for config. fork this just to make one.
