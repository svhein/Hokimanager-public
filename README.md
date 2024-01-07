## Hokimanager

&nbsp; &nbsp; As respect for [Maso Hockey Manager](https://fi.wikipedia.org/wiki/MHM) and [Hockey arena](https://www.hockeyarena.net/en/), __Hokimanager__ is text-based online mobile multiplayer game which simulates hockey team management - designed to be low effort, low time commitment but exciting game to play with other managers. <br>
&nbsp;&nbsp;   To lead hes team to success, manager has to manage team's roster, finances, training, tactics and more. In the heart of the game is it's hockey-game simulator, which is being built to deliver as realistic hockey game results as possible.

&nbsp;&nbsp;Each season contains 3-4 months and contains regular season, playoffs and relegation and promotion games. New players are welcome to the game anytime; spot from division and new team is assigned them automatically. 

## Technical details

![image](https://github.com/svhein/Hokimanager-public/blob/main/images/Hokimanager_block_diagram.jpg)

#### Frontend

- TypeScript
- React Native
  - Context API
  - React Navigation
- High dopamine UI design

#### Backend

- TypeScript & Node
- API build with Express
  - with team builder
- PostgreSQL database
- Scheduled microservice runner (runs once each day)
  - simulate the games of the day
  - daily finance operations
  - daily player operations
  - etc..

#### Game simulator

Game simulator takes both teams lineups & tactics as input

[![image](https://github.com/svhein/Hokimanager-public/blob/main/images/GameSimulator_diagram.jpg)


## Screenshots

few screenshots from mobile app

![image](https://github.com/svhein/Hokimanager-public/blob/main/images/LineupView.jpg)
![image](https://github.com/svhein/Hokimanager-public/blob/main/images/ResultCenterScreen.jpg)
![image](https://github.com/svhein/Hokimanager-public/blob/main/images/GameScreen1.jpg)
![image](https://github.com/svhein/Hokimanager-public/blob/main/images/GameScreen2.jpg)
