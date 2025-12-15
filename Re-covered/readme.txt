Re-covered 2.1

1. Options
    Use the mod "Respackopts" to access this resource pack's settings in-game.
    
    Alternatively, you can use your file explorer to change which files
    this resource pack should use.
    (!) Use the "/legacy_support/assets/minecraft/optifine/cit/vanilla/"
    directory if you're using Minecraft 1.21.4 or older.

    a) Disable animated textures
        Go to "/assets/carl/textures/item/" and replace the animated textures
        with the ones located in the "not_animated/" folder.
    
    b) Old animated textures
        Old versions of the animated textures for Respiration and Depth Strider
        can be found in the "/assets/carl/textures/item/alternative/" folder.
        Make sure to replace the .png.mcmeta files.

    c) Make the background of the recipe book button transparent
        Go to "/assets/minecraft/textures/gui/sprites/recipe_book/"
        and replace the textures with the ones located in the "transparent/" folder.

    d) Use an alternative texture for Quick Charge
        Go to "/assets/carl/textures/item/" and replace 'quick_charge.png'
        with one of the textures located in the "alternative/" folder.
    
    e) Pixelated Pack Icon
        In the root directory, replace the 'pack.png' file with 'pack_32x32.png'.

2. Changelog
    Update 2.1:
    - renamed en_US.json to en_us.json, so Respackopts can read the file when the pack is zipped
    
    Update 2.0:
    - 1.21.11 support
    - added Lunge texture
    - new Depth Strider animation
    - new Respiration animation
    - changed color of paper in all books to closer match vanilla
    - added [Respackopts](https://modrinth.com/project/TiF5QWZY) compatibility:
        - option to disable animations
        - variants for animation-disabled textures
        - option for transparent recipe book button background
        - alternative textures for Quick Charge
        - alternative pack icon
    - fixed one pixel in Unbreaking
    - fixed one pixel in Curse of Vanishing's animation
    - added license file
    - added readme file
    - updated pack.png
    - removed one line from enchanted_book.json
    - removed useless lines from model definitions
    - text formatting in png.mcmeta files
