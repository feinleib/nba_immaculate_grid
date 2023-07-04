# NBA Immaculate Grid
By Max Feinleib, July 2023

This game is an NBA version of [Immaculate Grid](https://www.immaculategrid.com/). For each spot in the grid, pick a player who’s played on both teams! (Awards and stat categories coming soon.)

## Getting started
1. Download the file `nba_immaculate_grid.Rmd` and the `data` folder, and place them in a folder together on your computer.
2. Open `nba_immaculate_grid.Rmd` in RStudio ([RStudio download link](https://posit.co/download/rstudio-desktop/))
3. Run all the code in `nba_immaculate_grid.Rmd` by pressing Command-Option-R
4. In the R Console, enter `play()` to play!

## Playing the game
1. You will see a 3x3 grid with an NBA team name for each row and column, and the 9 locations marked with the letters A-I.
2. To guess a player, enter a grid location and the player’s name. For example, if `GSW` is the first row and `OKC` is the first column, you could enter `A, Kevin Durant` to guess Durant for that spot.
3. You have 9 guesses, and you may not use the same player twice.
4. You can quit the game early by typing `quit`.

## More tips
1. **Game modes:**
  - **Daily:** This is the default game mode. Entering `play()` gives you today's game.
  - **Random:** To play on a random game grid, enter `play(daily = FALSE)`, or simply `play(FALSE)`.
  - **Replay:** You can replay your last game grid by entering `play(replay = TRUE)`.
2. **See answers:** When you’re not in the middle of the game, you can see all the answers for a pair of teams by entering `answers(“team1”, “team2”)`. (Example: `answers(“BOS”, “NYK”)`)
