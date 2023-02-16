# Target Game Practice

Nowadays many shooting games are on the rise in the gaming community.

Those games require extreme aiming capabilities by clicking at the accurate position as soon as possible.

I have build a game where gamers can practice their shooting aim.


## Pre requisites

 * [Python](https://www.python.org/downloads/) - 3.8.4 or up

### Installing

  - Download latest version of [Python](https://www.python.org/downloads/) :point_left:

    **1.** Go to the website above, and click on download

    **2.** Choose depending on which processor is your machine (in this example we looking to the files of Python 3.8.4)[Python](https://github.com/amssdias/PYTHON--School/blob/version1/img/python-download-versions.png)
      
    **3.** Double click and install (Add python to PATH just at the beginning of instalation)


### Run
 
 - Download the project, open terminal window on folder with 'school.py' and type:
 ```
 python target_game.py
 ```

## Functions

### `introduction`

It asks the user for his username and explains briefly the game.

### `game_levels`

In this function it simply displays the levels for the user to choose (Easy, Intermediate or Hard)

### `game_layout(username: str, difficulty: List)`

It takes two parameters, the username and the difficulty choosen from the previous function. In this function we display the game layout. On top a small bar with the username, points and the time running.

### `btn_position`

It simply redirects the target every time the user clicks on it, so it goes to a different place.

### `timer`

Timer will run the time, for 10 seconds, when it finishes it will display a new layout showing the user how many points he have made and a button if he would like to try it again.

### `reset`

This button just resets till where the user chooses the difficulty level.