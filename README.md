# PirateMaker

Project files for a Mario Maker inspired game
Made by Christian Koch / Clear Code

The code is public domain / CC0. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.
Attribution would be appreciated but is not required.
More information on the license: https://creativecommons.org/publicdomain/zero/1.0/

The artwork is from Pixelfrog and can be found here: https://pixelfrog-assets.itch.io/treasure-hunters
It is also published under a CC0 license.

The 2 pieces of background music are:
explorer theme - https://opengameart.org/content/8-bit-explorer-theme
adventure theme/ SuperHero - https://opengameart.org/content/adventure-theme

# 29_health

1. Add health-related attributes to the Player class in sprites.py
2. Update the Level class in level.py to accept an update_health function as a new argument in the init method, and call it when the player takes damage
3. Add ui files in graphics(coins,healthbar)
4. Add ui.py
5. Modify main.py to create an instance of the UI class, update the run method to display health, and pass the update_health function to the Level class

# TO-DO

1. Killing monsters
2. Collecting coins
3. Selecting mode(use editor maker or play default levels)
4. Game over setting(Falling out of map or collecting enough coins)
