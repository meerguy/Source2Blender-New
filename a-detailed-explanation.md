# ❔ A Detailed Explanation

## VPKs

VPK (Valve Pak) files are uncompressed archives used to package game content. Valve's post GCF games store materials, models, particles, choreography scenes and many other file types in VPK files.

## MDLs

MDL is the extension for Source's proprietary model format. It defines the structure of the model along with animation, bounding box, hit box, materials, mesh and LOD information. It does not, however, contain _all_ the information needed for the model. Additional data is stored in PHY, ANI, VTX and VVD files, and sometimes, usually for shared animations, other .mdl files.

## VMTs

A VMT ("Valve Material") file defines the material used by a two-dimensional surface. It contains all of the information needed for [![Source](https://developer.valvesoftware.com/w/images/thumb/1/10/Icon-Source.png/16px-Icon-Source.png)](https://developer.valvesoftware.com/wiki/Source) Source to simulate the surface visually, aurally, and physically.\
If a material is missing, it will produce the infamous Source pink and black checkered pattern. A white wireframe is not a missing material, but instead a missing shader.

## VTFs

The Valve Texture Format (VTF) is the proprietary texture format used by the [![Source](https://developer.valvesoftware.com/w/images/thumb/1/10/Icon-Source.png/16px-Icon-Source.png)](https://developer.valvesoftware.com/wiki/Source) Source engine. VTF files are generally referenced in a Material instead of being accessed directly, which allows re-use in different ways.
