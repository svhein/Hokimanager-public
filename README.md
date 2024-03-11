## Hokimanager

Multiplayer hockey team management game.
- each player manages own team
- games according to the match calendar
- season lasts 3 - 4 months
- creates new leagues dynamically when new users register

#### Game simulator
- crafted from bottom to up to provide realistic results
- flow of the game changes dynamically based on tacticts, lineups, heat detector, referees
- testing tools

 
## Technical details

![image](https://github.com/svhein/Hokimanager-public/blob/main/images/Hokimanager_block_diagram2.jpg)

#### Frontend

- React Native
  - Context API
  - React Navigation
- High dopamine UI design

#### Backend

- Node runtime
  - API
- PostgreSQL database
- Cloud functions
  - Game Simulator API
  - Daily scheduled tasks
- Firebase Auth
- GCP Cloud Storage
  

#### Game simulator

Game simulator takes both teams lineups & tactics as input

![image](https://github.com/svhein/Hokimanager-public/blob/main/images/GameSimulator_diagram.jpg)

#### Database diagram

![image](https://github.com/svhein/Hokimanager-public/blob/main/images/Hokimanager_Schema.svg)


## Screenshots

few screenshots from mobile app
<p float="left">
<img src='https://github.com/svhein/Hokimanager-public/blob/main/images/Lineup.jpg' width='300'>
<img src='https://github.com/svhein/Hokimanager-public/blob/main/images/ResultCenter.jpg' width='300'>
<img src='https://github.com/svhein/Hokimanager-public/blob/main/images/TeamView.jpg' width='300'>
<img src='https://github.com/svhein/Hokimanager-public/blob/main/images/GameScreen1.jpg' width='300'>
</p>

