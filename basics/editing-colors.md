---
description: >-
  This article explains everything you need to know about editing your color and
  color list!
---

# Editing colors

## The edit commands.

We have added the **/edit hex color** and the **/edit rgb color** commands when we added slash commands. They could seem difficult to use because of all of the different input options, but they are actually really simple to use!&#x20;

The following example is for changing a red color role to a blue one. You can either use the RGB version of the HEX version.

Example: **/edit rgb color new\_name:Blue r:0 g:0 b:255 name:Red**\
****Example: **/edit rgb color new\_name:Blue r:0 g:0 b:255 number:1**

Example: **/edit hex color new\_name:Blue hex:#0000FF name:Red**\
****Example: **/edit hex color new\_name:Blue hex:#0000FF number:1**

Almost everything is the same as the **add color commands** expect for the last input option, since you need to specify what color you want to edit. This is done with the **name** or **number** option, only one needs to be specified.

## Editing roles in the server settings.

You can also edit the color roles in the server settings. Be sure to use the **/update color list** command afterwards, to apply all the new changes to your list.

## Changing the order of colors.

This can also be done in the server settings! Simply drag a color role to a different position in the list and then update the color list again with the **/update color list** command.

{% embed url="https://cdn.colorchan.com/docImgs/ChaningRolePos.png" %}
Changing the role position.
{% endembed %}
