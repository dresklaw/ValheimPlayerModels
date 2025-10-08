# ValheimPlayerModels
![GitHub all releases](https://img.shields.io/github/downloads/dresklaw/ValheimPlayerModels/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/dresklaw/ValheimPlayerModels)

Use custom player models in Valheim!

# [DOWNLOAD](https://github.com/dresklaw/ValheimPlayerModels/releases/latest/download/ValheimPlayerModels.dll)
![preview](https://github.com/dresklaw/ValheimPlayerModels/blob/main/preview.png)
# How to install

 1. Download and install the [BepInEx package](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
 2. Drag and drop ValheimPlayerModels.dll in the "BepInEx/plugin" folder in your game install folder.
 3. Launch the game.
 4. Place all your avatars in the newly created "PlayerModels" folder inside your game install folder
 5. The mod will load the avatar with the same filename as your character name. (you might want to restart the game)

# How to create an avatar

 1. Install [Unity 2019.4.31](https://unity.com/releases/editor/whats-new/2019.4.31)
 2. Create a new 3D Project.
 3. [Download the SDK](https://github.com/dresklaw/ValheimPlayerModels/releases/latest/download/ValheimPlayerModels_SDK.unitypackage)
 4. Import the SDK and all your avatar assets.
 5. Change your avatar model rig to Humanoid if its not already setup from the import.
 6. Place your avatar model in the scene.
 7. Add a "Valheim Avatar Descriptor" component on your avatar.
 8. Click the "Auto-Setup" Button.
 9. Move the different equipment previews to fit your hands and the armour previews to fit your character.
 10. Change your avatar material shaders to "Valheim/Standard" or "Standard". Other shaders may have strange effects in-game.
 11. Click the "Export" button in the Avatar Descriptor.
 12. Export in the "PlayerModels" folder in your game install folder.
