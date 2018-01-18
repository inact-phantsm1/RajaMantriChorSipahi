# Raja-Mantri-Chor-Sipahi https://prashantchhabra89.github.io/Raja-Mantri-Chor-Sipahi/
Raja(Prince)-Mantri(Minister)-Chor(Thief)-Sipahi(Police) is a classical indian game.</br>
4 players play the game. Each player gets role of either a Prince, Minister, Thief or Police.
The player who gets the role of a prince asks "who is my minister?"
Minister reveals that "I am your minister".
Prince then says "You have to figure out who is thief and who is police".
Minister makes the guess.

### Score
Prince gets 1000 points and plice gets 500 points
If miniter's guess was correct, miniter will get 800 points else 0.
Theif will get 800 points if minister's guess was wrong else 0.
This game can continue as long as everyone wants to play or winner can be declared when any player reaches 10000 points.

### Instructions
#### How to run locally?
⋅⋅* Make sure git and node is installed
⋅⋅* Clone repo using git clone
⋅⋅* npm install
⋅⋅* npm start
⋅⋅* It will open browser with app running at localhost:3000/
⋅⋅* To stop in cmd use ctrl+c
#### How deploy on github?
⋅⋅* Edit package.json by adding a new field named homepage: "homepage": "https://<github-username>.github.io/<projectrepo>"
⋅⋅* npm run build
⋅⋅* npm install --save-dev gh-pages
⋅⋅* Add a new script to the scripts field inside package.json. Let’s call the script deploy : "deploy" : "npm run build&&gh-pages -d build"
⋅⋅* npm run deploy
⋅⋅* Now go to repo page on github->settings
⋅⋅* it should say "Your site is published at ...."

