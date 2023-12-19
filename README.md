# Score Keeper App

## Overview
The Score Keeper App is a simple, interactive web application built using React. It allows users to keep track of scores in a game. The app provides an easy-to-use interface for incrementing scores and adding comments for each score update.

## Features
- **Score Buttons**: Buttons for each possible score increment (0-6) and a button for wickets.
- **Score Display**: Real-time display of the current score and wickets.
- **Comment Input**: Allows users to add a comment for each score update.
- **Score History**: Displays a history of all score updates with their associated comments.

## How to Use
1. Click on the score button that corresponds to the number of runs scored in the last play.
2. If a wicket fell, click on the 'Wicket' button.
3. Add a comment in the input field if desired.
4. Click 'Submit' to update the score and add the comment to the score history.

## Code Structure
The code is structured into several React components:
- `App`: The main component that renders the entire application.
- `ScoreButtons`: Renders the score buttons.
- `Form`: Renders the input field for comments and the submit button.

## Dependencies
- React
- ReactDOM
- Babel

## Future Improvements
- Add functionality for multiple innings.
- Add player statistics.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

