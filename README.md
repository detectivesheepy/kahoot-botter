
# kahoot-botter

A GUI for a simple Kahoot spammer, brought back from the dead.

## Installation
Open your windows terminal and run this code:
``git clone https://github.com/detectivesheepy/kahoot-botter.git``.
Then run the ``index.html`` file inside the folder. I reccomend creating a shortcut to the ``index.html`` for quick and easy access.

## How to use the GUI

### Inputs

|Input|Meaning|
|--|--|
| name | this will be the base name that the bots will join with |
| pin | the pin that the bots will join |
| number of bots | amount of bots to join (or if a specific name list is chosen in the advanced settings, the amount of times each name joins) |
| join delay | millisecond delay between each bot joining (minimum 50) |

### Buttons

|Button|What it does|
|--|--|
| Deploy bots | starts making the bots join |
| Toggle advanced settings menu | opens the advanced settings menu (see below) |
| Console: toggle show| shows the console |
| Show quiz infos | opens some quiz info that will be shown on the right side of the screen (WIP) |
| Kill bot spawner | stops bots from spawning |
| Force all bots to leave | makes all the currently joined bots leave |

### Advanced settings

| option | Meaning |
|--|--|
| prefix+number | Makes all bots join using the format (where prefix is the bot's name) |
| number+suffix | Makes all bots join using the format (where prefix is the bot's name) |
| from list | Disables the normal name input and all bots will join using a name from there. If the amount value is 1, then every bot on the list will join, if it's 2 every bot will join twice |
| Save | saves |
