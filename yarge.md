# **VOXEL ENGINE**
This Engine iwill contain many interesting features such as Fluid Physics, Terrain generation and a lot of voxels. The Engine is written "from scratch" in Vulkan, specifically the vulkano crate of rust.

## GraphicsBackends
* Vulkan 3.5
* ~~D3D12~~ 

## Light
* Light Types
  * ~~Point Light~~
  * Directional Light
* Shadows
    * shadow for main directional light (wip)
* supported light algorithms
  * PBR (without skybox reflections)
  * Blinn-Phong

## Debug
* Debug objects 
  * cubes
  * lines
* imgui
  * Different imgui windows for showing the hierarchy, object data, fps and shadow maps or other textures like atlases

## GLTF
* Load GLTF files, currently only supports v1, loads the indices, vertices, textures and animations 

## Mesh
* Meshes

## GameObjects
* Components
  * Components can be attachted to gameobjects and will update evey frame;
  * There are components such as
    * Audio Source
    * Animator
* Scripts
    * Scripts can also be attached to gameobjects and have a start and update functions, which are called respectively;
* Hierarchy
    * Gameobjects can have children and parents

## UI
* UI currently draws text with different colors and fonts and images

# Other
* Skybox, supported skybox from 6 pngs and .env (wip)

# Features to add
* Terrain
  *
  * ~~Wind~~
* Lighting, clustered lkighting\
* Voxels
