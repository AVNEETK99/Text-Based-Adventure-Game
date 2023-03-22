# Text-Based-Adventure-Game

A text-based adventure game is a type of game where the player interacts with a story or world through text-based input and output. These games are typically presented in a text-only interface, and the player types in commands to control the actions of their character, explore the environment, solve puzzles, and interact with other characters.

In a text-based adventure game, the story is typically presented in the form of descriptive text, and the player's actions are also described through text. For example, the game might present a scenario like "You are in a dark room. You can see a door to the north and a chest on the floor. What do you want to do?" The player might then type "open chest" or "go north" to interact with the game world.

Text-based adventure games can be very immersive and engaging, as they rely on the player's imagination and creativity to fill in the details of the story and environment. They can also be very challenging, as players must rely on their own intuition and problem-solving skills to progress through the game.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python textgame.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The code begins by defining two lists, ```answer_yes``` and ```answer_no```, that contain possible positive and negative responses from the user.
* The program then displays a welcome message and a scenario where the user is driving home and encounters a woman who asks for a ride.
* The program prompts the user to answer whether they will give the woman a ride or not by accepting user input using the ```input()``` function and storing it in a variable called ans1.
* If the user's response is in the ```answer_yes``` list, the program asks another question where the user has to choose whether to admit seeing the suspicious woman or not.
* If the user admits to seeing the woman, the program prints a congratulatory message saying that the user has won the game.
* If the user denies seeing the woman, the program prints a message saying that the user helped a murderer and the game is over.
* If the user's response is in the ```answer_no``` list, the program asks another question where the user has to choose whether to knock the woman down or not.
* If the user decides to knock her down, the program prints a congratulatory message saying that the user helped the police catch the murderer.
* If the user chooses not to knock her down, the program prints a message saying that the user is dead, the woman was a murderer, and the game is over.
* If the user's input is not in either ```answer_yes``` or ```answer_no```, the program prints a message saying that the user typed the wrong input and ends the game.

