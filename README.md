
# 3D Studio Max VTF import plug-in
A plug-in for 3D Studio Max for importing VTF format texture files used with Source engine based games.

## Overview
This is a simple Max plug-in to allow Valve VTF texture files to be loaded into max directly as textures. It supports most of the VTF compression formats.

The plug-in loads the largest image for the first frame of the VTF. If its a cube/environemt map VTF, it will load the first face. Same for animated textures. HDR images are downsampled to 8-bit from 16-bit before import.

Textures are converted to and loaded as 32-bit RGBA into Max.

## Supported versions
* 3DS Max 9    - 32/64bit
* 3DS Max 2008 - 32/64bit
* 3DS Max 2009 - 32/64bit
* 3DS Max 2010 - 32/64bit
* 3DS Max 2011 - 32/64bit
* 3DS Max 2012 - 32/64bit
* 3DS Max 2017 - 64bit
* 3DS Max 2018 - 64bit
* 3DS Max 2019 - 64bit
* 3DS Max 2020 - 64bit

## Installation

**Note**: If you have a previous version of the plug-in installed, please delete it first! This version has a different filename than older versions so if you already have `vtf.bmi` or `VTFImporter.bmi` in your MAX plug-ins directory, delete it.

### Plug-in installation

Copy the `VTFImporter.bmi` file for the correct version for your edition of 3D Studio Max into your 3DS Max plug-ins folder (i.e. `C:\Program Files\Autodesk\3ds Max 2019\Plugins`) and re-start. You can check it's loaded via the Plug-ins Manager.

For Max 2017 onwards, which are 64-bit by default, the plugin filename is `VTFImporter.bmi`

### VTF Lib

This plug-in requres [VTF Lib](https://github.com/NeilJed/VTFLib) which can be found in the `VTFLib` folder. Copy the correct file for your version of 3DS Max and place it in the program folder, i.e. `C:\Program Files\Autodesk\3ds Max 2019`

## Basic usage
Once installed you should be able to use VTF file as an image type for textures.

## Legal

### Author
This software was created by and is &copy; 2011 Neil "Jed" Jedrzejewski

### License & Warranty
The content owner grants a non-exclusive, perpetual, personal use license to view, download, display, and copy the content, subject to the following restrictions:

1. The content is licensed for personal and non-profit use only, not commercial use. The content may not be used in any way whatsoever in which you charge money, collect fees, or receive any form of remuneration for commercial gain. The content may not be resold, relicensed, sub-licensed, rented, leased, or used in advertising.

2. Title and ownership, and all rights now and in the future, of and for the content remain exclusively with the content owner.

3. This software is provided 'as-is', without any express or implied warranty.

4. The content owner will not be liable for any third party claims or incidental, consequential, or other damages arising out of this license or the use of the content.

5. This notice must NOT be removed or altered from any distribution of this software.
