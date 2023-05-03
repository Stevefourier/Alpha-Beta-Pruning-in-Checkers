# Alpha Beta Pruning in Checkers - Artificial Intelligence
## Alpha Beta Pruning in Checkers Game


This is an official link to the [Checkers game](https://www.officialgamerules.org/checkers) game to be able to undertand fundamentally how the game is played.



## How to play the Checkers Game
This game is run by executing the `game.py` module.

```python
def input_forced_moves():
    while True:
        forced = input(
            "Do you want to enable forced captures? <yes|no>:")
        try:
            if forced.lower() == "yes":
                return True
            if forced.lower() == "no":
                return False
            print("Invalid choice! Try again.")

        except:
            print("Invalid input! Try again!")

```