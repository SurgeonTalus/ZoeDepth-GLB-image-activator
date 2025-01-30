# ZoeDepth GLB Image Activator Addon for Blender

## Overview
When using **ZoeDepth**'s "Image to 3D" feature, the resulting `.glb` file may lack the image or color information. This addon restores the image projection by adding a **Principled BSDF** shader with an **Attribute node** connected to the **Base Color** input.

This addon adds a button under the **Object** menu called **"Apply ZoeDepth image on GLB file"**, which automatically applies the necessary shader and restores the image stored within the `.glb` file.

![Apply image to .glb from ZoeDepth](https://raw.githubusercontent.com/SurgeonTalus/ZoeDepth-GLB-image-activator/main/Apply%20image%20to%20.glb%20from%20ZoeDepth.png)

## Features
- Restores the image/color information for `.glb` files exported from ZoeDepth.
- Automatically creates a **Principled BSDF shader** with the image attribute connected to the **Base Color**.
- Simple integration into Blender's UI under **Object > Apply ZoeDepth image on GLB file**.

## Installation

1. Download the `.zip` file from the releases section or clone this repository.
2. Open Blender.
3. Go to **Edit > Preferences > Add-ons**.
4. Click **Install** and select the downloaded `.zip` file.
5. Enable the addon by checking the box next to **ZoeDepth GLB Image Activator**.

## Usage

1. Open your `.glb` file in Blender.
2. Select the object to which the image needs to be applied.
3. Go to the **Object** menu in the 3D Viewport.
4. Click the button labeled **"Apply ZoeDepth image on GLB file"**.
5. The addon will automatically create a new **Principled BSDF shader** and link the image stored in the `.glb` file to the **Base Color**.

## Notes
- This addon works with `.glb` files that contain image data exported from **ZoeDepth**.
- Ensure that the image is properly projected onto the object in ZoeDepth before exporting the `.glb`.

## License

This addon is released under the **GPL-3.0** license.

## Author

**Sondre Ileby**

Feel free to contribute or report issues through the GitHub issue tracker.
