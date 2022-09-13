# FBX Files and Textures

## The PH2 Level Editor

Perfect Heist 2 expects two files per custom model (check out "HOW-TO add custom objects" in [this guide](https://steamcommunity.com/sharedfiles/filedetails/?id=2802780434)).

To have a custom model named `custom-model` in the level editor, there must be these two files:
- `custom-model.fbx`: The actual 3D-model
- `custom-model.png`: The texture (colors etc.) of the model

Our *Model Inspector* does this for us, as long as the models are correctly loaded in the model browser.

## Model Files and Textures for the Model Browser

When you have a folder with some `.fbx` files and you load them into the inspector, they should already be displayable and can also be copied to custom maps. The more complex parts are the textures. Many FBX models have shared textures to save disk space. They cannot be detected by the model inspector. By default, the inspector expects the model and texture to have the same name and be in the same directory, just like the level editor.
But you can set shared textures manually for a whole directory to make it easier.

## Setting Textures

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/set-texture?raw=true" width="800">

You can set or change the texture of a single model or of all models within a directory (and its subdirectories). To do this, right click on it in the model browser **(1)** and select "set texture" in the context menu **(2)**. This will open the following file browser:

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/texture-browser.png?raw=true" width="800">

Select the `.png` texture you want to use and confirm your selection with *"Select File"*. This will instantly assign the texture.