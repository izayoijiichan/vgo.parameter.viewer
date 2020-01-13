# VGO Parameter Viewer
This is a viewer that displays the parameters in the VGO file.

![image1](https://github.com/izayoijiichan/vgo.parameter.viewer/blob/master/images/screenshot_1.png)
![image2](https://github.com/izayoijiichan/vgo.parameter.viewer/blob/master/images/screenshot_2.png)
![image3](https://github.com/izayoijiichan/vgo.parameter.viewer/blob/master/images/screenshot_3.png)

## Description
Reads the specified VGO file and displays glTF and VGO extended information.

## Requirement
- Windows 10
- .NET Framework 4.5
- Newtonsoft.Json.dll 12.0

## Installation
Download exe and place it anywhere.

## Usage
1. Launch exe.
2. Specify VGO file.
    - Press the 'Open File' button and select the file in the dialog.
    - Drag and drop the VGO file onto the form.
    - Specify the path to the VGO file with command line arguments at startup.

## Specification Version
- glTF JSON Schema: [2.0](https://github.com/KhronosGroup/glTF/tree/master/specification/2.0/schema)
- VGO JSON Schema: [0.3](https://github.com/izayoijiichan/VGO/tree/master/Documentation~/VGO/specification/0.3/schema)
- UniVGO: v0.5.0 (14 Jan, 2020)

## Implementation
- glTF
  - accessors
  - animations (unimplemented)
  - asset
  - buffers
  - bufferViews
  - cameras (unimplemented)
  - images
  - materials
  - meshes
  - nodes
    - extensions
      - VGO_nodes
        - gameObject
        - colliders
          - collider
            - physicMaterial
        - rigidbody
        - light
        - right
  - samplers
  - scene
  - scenes
  - skins
  - textures
  - extensions
    - VGO
      - meta
      - right
  - extras

## Link
- [VGO](https://github.com/izayoijiichan/VGO)
