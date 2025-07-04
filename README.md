# Real Snow Mesh (Modified for Blender 4.3 and 4.4)

This is a modified version of the **Real Snow** Blender add-on, originally developed by:

- Marco Pavanello  
- Drew Perttula

**Original Project**  
- [Blender Extensions: real_snow](https://projects.blender.org/extensions/real_snow)  
- [GitLab Repository](https://gitlab.com/marcopavanello/real-snow/)

## Modifications by

**Ron Taulbee (2025)**  
Contact: [ron.taulbee@gmail.com](mailto:ron.taulbee@gmail.com)

📌 See the [Roadmap](ROADMAP.md) for future development plans and tracking.


## Description

This modified version updates the add-on for compatibility with Blender 4.3 and 4.4. Changes include:

- Replaced deprecated material node input indices with named inputs.
- Updated shader socket types (e.g., *Specular*, *Subsurface Radius*) for Blender 4.3’s stricter API.
- Adjusted Voronoi Texture node output handling for `N_SPHERE_RADIUS` mode.
- General code cleanup and improved version tagging.
- **Tested on:**  
  - Linux (Ubuntu 22.04)  
  - Blender versions: 4.3.2 and 4.4.3

## License

This add-on is licensed under the **GNU General Public License v3.0 or later**.  
A copy of the full license text is provided in the `LICENSE.txt` file.

## Redistribution

You are free to use, modify, and redistribute this software under the terms of the GPL.  
If you distribute this modified version, you must:

- Include the full source code.
- Retain the original copyright.
- Include both the `README.md` and `LICENSE.txt` files.

## Installation

1. Download or clone this repository.
2. From Blender, open **Edit > Preferences > Add-ons**.
3. Click **Install...** and select the `.zip` archive of this folder or copy the folder directly into your Blender add-ons directory.
4. Enable the add-on by checking **Real Snow Mesh** in the list.
