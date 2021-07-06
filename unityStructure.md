# File Structure
===
Assets/
: Carpeta de Unity donde se encuentran todos los recuersos a utilizar para el desarrollo del videojuego

Scenes/
: Carpeta donde se encuentran las escenes .unity

Scripts/
: Carpeta donde se encontrarán todos los scripts del videojuego

Resources/
: Carpeta donde se encuentran recursos como: audios, modelos, prefabs, sprites

Prefabs/
: Carpeta para los objetos prefabricados

Sprites/
: Carpeta para los sprites del videojuego que no seran optimizados

```
Assets
|
|-- Scenes
|    |-- [ScenesFolder]
|           |-- Scene.unity
|
|-- Scripts
|    |-- [sceneFolder]
|    |-- [generalFolder]
|
|-- Resources (minigames)
|    |-- [audioFolder]
|    |      |-- [sceneFolder]
|    |-- [spriteFolder]
|    |      |-- [sceneFolder]
|    |-- [prefabFolder]
|           |-- [sceneFolder]
|
|-- Prefabs
|    |-- [sceneFolder]
|    |-- [generalFolder]
|
|-- Sprites
|    |-- [sceneFolder]
|    |-- [generalFolder]
```
## Carpetas Especiales

Editor/
: Carpeta para los scripts y recursos de editor (que no estarán en el **Build** Final)

StreamingAssets
: Carpeta que contiene los recursos comprimidos desde la carpeta de **Resources**

UAP/
: Carpeta para el Plugin de accesibilidad
---
```
Assets
|
|-- Editor
|
|-- StreamingAssets
|
|-- UAP
```


[Home](./index.md)