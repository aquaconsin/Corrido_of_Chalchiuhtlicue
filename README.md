# Corrido of Chalchiuhtlicue

An attempt at a cli based aquarium planning calculator written in python

release coming soon. currently not operational but being worked on

-----

## Usage:

The settings file should be able to be editted both in the program as well as by hand via a txt editor as well as many of the aqu files but be careful not to break the functionality

Exit the program using `CTRL + C`

### Steps to run on ubuntu:

There are prereq installs for pip but currently I do not know which. Once Ive had a chance to look into that this will be updated

  1. Copy the project files to their own folder
  2. `python3 ./fishcalc.py`
     
       The program will then begin creating its own file tree within which it will operate
       when the main menu is brought up if you have cards already you can exit and continue preparations
     
  3. If you have cards to use to start with this is where you add them. Otherwise this will be where you will do initial setup
    A. If you have cards sorted into folders already you can add them or if you they arent sorted you can add them to the import folder and then it will run during the next program start.
    B. If you do not have any cards you may have to open the card viewer option and create them. The optimal order to create them in is going category by category for food, fish, tank, fishroom so that you wind up backtracking the least adding things later.

### Steps to run on windows/macos:
Currently do not have access to either of these nor an interest in them. If someone knows how to run this on those and can tell me a tutorial on I will eventually get to adding those here
My understanding as it stands is that these are the steps on windows at least:
  1. Install python 3
  2. Install pip
  3. Install requirements (stated above maybe)
  4. Open command line
  5. type in `python3 ./fishcalc.py` and it should run? (I have never attempted this before but read it on another github page once)

-----

## Note to Consider
When editting files using this program it does not consider readability for later at times. This is something which I will need to fix later but for now this means if you edit something wrong you will have to be the one to fix it and it might not be obvious how its wrong to anyone else. So when possible its best to stick to edits which you are confident in making

_________________________________________________________________________
## Information referenced within

[this is the equation used for food mg to ammonia ppm used](https://www.sosofishy.com/post/how-to-calculate-how-much-your-feeding-produces)

[this is a page used to research food as well. useful for creating the initial food cards](https://aquariumscience.org/index.php/3-6-1-dry-fish-food-in-depth/)


## Major issues not yet fixed

>[!WARNING]
> 1. Currently theres an issue with showing tables incorrectly when not showing in fullscreen. At some point I plan to fix this but currently theres other issues that Im working on. If anyone has advice on code to change to fix that please open it as an issue with your advice

## Currently working features 
** Expect the below to bounce up and down as things are added **
- Water change quick reference calculator
- Min/Max shoal size calc
- Ph calculation
- Temperature calculation
- Daily nitrate production calc based on food input


## Hoping to get working features
- Warning if cant be housed with fish
- Sex ratio calculator and warning system
- Fishroom temperature heater needs calculator
- Multiple food sources per fish
- Plants (its looking a bit more complicated than expected for the ideas I originally had)
- Jumper/tank lid warning (maybe with water hieght reduction advice based on jump hieght but probably not - would need to take into account during water changes and stocking as well as other unforeseen areas)
- some kind of version id so that cards can be updated if need be 






