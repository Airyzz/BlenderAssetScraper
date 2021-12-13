# BlenderAssetScraper

A blend file containing scripts to automatically download and catalog assets from online asset libraries.

### If you make use of this script, please consider supporting the creators of the assets.

## Supported libraries:
[ambientCG.com](https://ambientcg.com/) [(Support Here)](https://www.patreon.com/ambientCG)

(If you have other library requests, feel free to open an issue)

## How to use:
- Download and open the .blend file from this repo. 
- Change the variable `file_path` to point to where you want the texture files to be stored
- Make sure to open the system console `(Window > Toggle System Console)`, as Blender will appear to be frozen during execution of the script
- Run the script!

All assets will be automatically downloaded, and marked as an asset, ready for use with the Blender 3.0 Asset Browser!

This script will automatically skip over any assets which already exist in the blend file, meaning you can run this script again at a later date, and it will only download new assets which you don't already have

I recommend to keep the texture quality to only 1K or 2K, as downloading 1000+ 8K textures will use a considerable amount of storage space and memory.
