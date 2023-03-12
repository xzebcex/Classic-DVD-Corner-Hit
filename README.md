# **Classic DVD Corner Hit**

## Description
This is a straightforward Python script that mimics the classic DVD logo corner hit animation. It generates one or more different-colored DVD logos and moves them around the terminal screen, bouncing them off the edges and changing their direction and color when they reach a corner.

## Table of Contents
1.	Installing and Running
2.	How to Use
3.	How to Contribute
4.	Additional Points
5.	Conclusion

## Installing and Running
Python 3 and the 'bext' module are required to run this script. You can install 'bext' in your terminal by typing pip install 'bext'.
After installing Python 3 and 'bext,' you can run the script by going to its directory in your terminal and typing python classic_dvd_corner_hit.py.

## How to Use
When you run the script, one or more DVD logos will move around the terminal screen. You can change the following constants to alter the script's behaviour patterns:
1.	NUMBER_OF_LOGOS: The number of logos to generate.
2.	PAUSE_AMOUNT: The time (in seconds) to pause between frames of the animation.
3.	COLORS: The list of possible colors for the logos.
4.	DIRECTIONS: The list of possible directions for the logos.
You may also experiment with commenting out or modifying some of the lines of code in the main() method to change the behaviour of the logos.
To stop the animation, use Ctrl-C on your keyboard..

## How to Contribute
If you find a bug or have an improvement suggestion, please create an issue or submit a pull request to the github repo.

## Additional Points
The bext module is used to clean the terminal screen, move the cursor, and change the text color.
The logos move diagonally by modifying their X and Y coordinates by varying amounts based on their direction.
As a logo comes to a corner, its direction is modified and its color is picked at random from a list of available colors.
The animation loop will continue endlessly unless the user stops it.

## Conclusion
The "Classic DVD Corner Hit" application is an entertaining and interactive animation that creates logos that bounce about the screen. To modify the terminal display and produce the animation, the application makes use of the 'bext' library. The user may change the amount of logos, the pause time between motions, and the colors utilized. The application also records and displays the number of times the logos hit the corners.
