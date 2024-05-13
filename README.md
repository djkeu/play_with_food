# Play with food

## Description:


### Introduction
Project title: Play with food\
Name: Marc Kooij\
GitHub: djkeu\
City: Leeuwarden\
Country: The Netherlands\


### A small summary
Play with food is a game in which the player is to look for several ingredients and combine them into a meal. As the game advances, the player is to perform more (difficult) tasks, like buying the food, looking for shops, etcetera.\

First edition will be a Scratch or text-based Python program.


### Running the program
The Python version is executed in the terminal, by typing 'python main.py'. The program does not take any command-line arguments.\
The Scratch version is to be run on https://scratch.mit.edu/


### Gameplay
Only certain combinations are allowed to be combined into a meal. User is to choose ingredients from several lists.


### File-structure

The program has the following file-structure:
##### (Yet to be determined)

#### Python version
- ./play_with_food
    - /img
        - ingredient01.png
        - ingredient01_tn.png
        - meal01.png
        - meal01_tn.png
        - *.png/jpg/jpeg/gif
    - /txt
        - user_directions.txt
        - *.txt
    - ingredients.json
    - main.py
    - play_with_food.py
    - README.md
    - requirements.txt
    - test_main.py



play_with_food/
    play_with_food.py # this is the program you run.
    play_with_food_lib/
        __init__.py
        main.py
        MainWindow.py
        ClassThing.py
        function_thing.py
        ...

My AppName.py contains incredibly sparse boilerplate code. A copyright header, some comment about what the app does... Usually it just imports AppNameLib and calls main.py, for a total of about 5 lines of actual code.

main.py will handle all of the argument processing and setup code, set any constants (if appropriate), create my MainWindow instance if it has a user interface, start event loops... but it is also pretty sparse. Maybe a few dozen lines. 