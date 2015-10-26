# Decompiling

In this tutorial we will learn on how to decompile maps to edit them or learn from them. :D

## Prerequisites

You will need to have Radiant installed, but I'm pretty sure you already have it. :P (I'm using GtkRadiant 1.5)

## Making a batch file

Create a new .bat file in your GtkRadiant directory, and copy the following code into it :

```batch
echo off
cls
title Map Decompiler
q3map2.exe -game et -convert -format map "%~1"
pause
```

## Finding the map

You are all ready to decompile maps, but you need to have maps to do so. :P
Go into your Wolf:ET folder and look for the map you want in the etmain directory, then, open the pk3 file with PakScape, 7Zip, or whatever program you use for opening .pk3 files, go in maps, and take the file that has ends with .bsp.

## Decompiling the map

Drag the .bsp file on the batch file you create earlier, wait some secs, and a new file called mapname_d.map will be created.
Now you can open the map in Radiant and do whatever you want with it.

## Notes

* Don't claim the map as your own when you just changed some textures and added some crates, decompiling is mostly intended for learning how things are done in maps!
* The textures will be misaligned, you must fix that on your own.
