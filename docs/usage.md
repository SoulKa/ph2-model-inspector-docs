# Usage

Download and start the *PH2 Model Inspector* as described [here](https://soulka.github.io/ph2-model-inspector-docs/#how-to-run).

## Map Selection

If you don't have any custom maps on your computer, continue to read the next section.
Otherwise, you will see a menu like this:

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/map-browser-annotated.png?raw=true" width="800">

Each of your custom maps is shown with its preview image **(1)**. By clicking on it you will select that map as working target.
Alternatively, you can skip the map select **(2)**. If so, you can only browse your local 3D models.

## 3D-Model Browser

### Map Models
When first going to the model browser, the screen will be quite empty:

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/model-browser-no-dir-annotated.png?raw=true" width="800">

If you selected a map in the previous step, you will see the map name **(1)**, and its custom FBX models **(2)**. Each model is represented by its name and a small cube icon. A *blue* icon means that the model has a texture set, while a grey icon represents a model without a texture.

To select a directory that contains your custom FBX 3D-models, click the folder icon in the navigation bar **(3)**. A filebrowser opens where you should select the model directory. Alternatively, you can just paste the filepath to your directory and press *"Load Models"* (goto the next section).

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/model-browser-select-dir-annotated.png?raw=true" width="800">

The filebrowser shows your currently selected directory path on the bottom **(1)**. You can change the current directory by double clicking a folder, or clicking a directory in the current path **(2)**. Once you selected the correct folder, click the *"Select Folder"* button **(3)**.

### Model Browser

<img src="https://github.com/SoulKa/ph2-model-inspector-docs/blob/main/screenshots/model-browser-annotated.png?raw=true" width="800">

If the selected directory, or any of its sub-directories contains `.fbx` files, they will show up in the *model browser* **(1)**. The models are again represented by a cube icon in the list **(2)**. When you click on a model, it shows up in the model renderer **(3)**. You can rotate and zoom the model as you wish by clicking and holding the rendered 3D-model.

To add a model from the *model browser* to your map, click on the *green cube icon* **(4)**. The `.fbx` file and its `.png` texture file are copied into the PH2 map directory. If you are in the level editor of Perfect Heist 2 for the selected map, the custom model should be available instantly.

To delete a custom model from a map, press the *trash icon* **(5)** in the map model browser. Note that this will delete the `.fbx` and `.png` files *inside the map directory*. The files in your selected model directory are not modified in any way.

### FBX Model Files and Textures

If you have missing textures or other file related questions, check out [this section](https://soulka.github.io/ph2-model-inspector-docs/files-and-textures).