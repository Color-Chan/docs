---
description: Don't know how to add colors? Everything about adding is explained below!
---

# Adding colors

## Adding a default color list.

{% hint style="warning" %}
Default color lists can only be added if your color list is empty.
{% endhint %}

A default color list with 8 colors can be added with one simple command!\
You can use the **/add default colors** for this.

{% embed url="https://cdn.colorchan.com/docImgs/AddDefaultColors.png" %}
The default color list.
{% endembed %}

## Adding a random color.

You can also add random colors with the **/add random color** command. Or you can use the **/suggest color** if you want a suggestion on what colors you could add.

## Adding specific colors.

You can add specific colors with a color name and a HEX code or a RGB code.&#x20;

{% hint style="info" %}
More information about color codes can be found [here](https://htmlcolorcodes.com/color-picker/). You can also find a list of 140 named colors [here](https://htmlcolorcodes.com/color-names/), incase you are having trouble thinking of any names for your colors.
{% endhint %}

* Red: **/add hex color name:Red hex:#FF0000** or **/add hex color name:Red r:255 g:0 b:0**&#x20;
* Green: **/add hex color name:Green hex:#00FF00** or **/add hex color name:Green r:0 g:255 b:0**&#x20;
* Blue: **/add hex color name:Blue hex:#0000FF** or **/add hex color name:Blue r:0 g:0 b:255**&#x20;

## Adding existing color roles.

You can also add existing color roles with the **/add existing color** command.\
Example: **/add existing color role:@Red**

## **Importing a color list from a different server.**

It is also possible to import an existing color list from a different server. You will need to get the export ID with **/export color list**. You can import the existing list with the following command after you have gotten the export ID: **/import color list id:123456**

## **Deleting color roles**

{% hint style="danger" %}
_Clearing the color list or deleting color roles is **irreversible**. You will have to create the deleted color roles again._
{% endhint %}

You can delete colors with the **/delete color** command once you have added one or more color roles to your color list. Example: **/delete color number:1** or **/delete color name:Red**.

It is also possible to delete the whole color list at once. You can do this with the **/clear color list** command.
