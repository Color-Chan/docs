---
description: A list of the commands for Color-Chan!
---

# Commands

{% hint style="info" %}
**All of Color-Chan's commands have moved to slash commands since November 6th.**

**This change is inevitable**, as starting in April 2022, verified bots in 75 servers or more will need to change to slash commands. More info can be found [here](https://support-dev.discord.com/hc/en-us/articles/4404772028055.).\
**Custom prefixes have also been removed during this move**. Color-Chan's prefix is now **/**
{% endhint %}

{% tabs %}
{% tab title="Basic commands" %}
### /help

Return a list with all the commands for Color-Chan.\
Example: **/help**

### **/getting started**

Returns a guide on how to get started with Color-Chan.\
_Example: **/getting started**_

### /setup

Returns a guide on how to setup Color-Chan.\
_Example: **/setup**_

### /add hex color

Adds a color role to the color list using a HEX color value.\
_Example: **/add hex color name:Hotpink hex:FF69B4**_

### _/add rgb color_

Adds a color role to the color list using a RGB color value.\
_Example: **/add rgb color name:Hotpink r:255 g:105 b:180**_

### _/add random color_

Adds a random color role to the color list.\
_Example: **/add random color**_

### _/add default colors_

Adds a default list of colors to the color list.\
_Example: **/add default colors**_

### _/remove color_

Removes your current color role.\
_Example: **/remove color**_

### _/color list_

Returns the color list of this server.\
_Example: **/color list**_

### _/delete color_

Deletes a color role from the color list.\
_Example 1: **/delete color name:Hotpink**_\
_****Example 2: **/delete color number:1**_

### _/set random color_

Changes the color of your name to a random color!\
_Example: **/set random color**_

### _/set color_

Changes the color of your name!\
_Example 1: **/set color name:Hotpink**_\
_****Example **** 2: **/set color number:1**_

### _/set members color_

Changes the color of a server member's name!\
_Example 1: **/set members color user:@BrammyS#0001 name:Hotpink**_\
_****Example 2: **/set members color user:@BrammyS#0001 number:1**_
{% endtab %}

{% tab title="Color reaction commands" %}
### /reaction lists

Returns a list of all the current reaction lists.\
_Example: **/reaction lists**_

### _/delete reaction list_

Deletes a specific reaction list.\
_Example: **/delete reaction list id:123456**_

### _/add reaction color_

Adds a reaction color to a color reaction message.\
_Example: **/add reaction color name:Hotpink**_\
_****Example: **/add reaction color number:1**_

### _/add reaction colors_

Add all the color roles to color reaction lists.\
_Example: **/add reaction colors**_

### _/toggle reaction messages_

Toggles the messages when reacting to a color reaction list on or off.\
_Example: **/toggle reaction messages**_

### /clear reaction lists

Clears all the current reaction lists. **Note: This is irreversible!**\
_Example: **/clear reaction lists**_
{% endtab %}

{% tab title="Advance commands" %}
### **/color info**

Returns some information about a color role.\
_****Example: **/color info name:Hotpink**_\
_****Example: **/color info number:1**_

### **/import color list**

Imports an existing color list using an export ID.\
_****Example: **/import color list id:12345**_

### **/export color list**

Gets a unique ID used to import the color roles of this server to a different one.\
_****Example: **/export color list**_

### _**/**_**update color list**

Updates the color list, can be useful when roles were accidently removed or to apply a role edit.\
_****Example: **/update color list**_

### _**/add existing color**_

Adds an existing color role to the color list.\
_****Example: **/add existing color role:@Hotpink**_

### **/clear color list**

Clears the color list. Note: This is irreversible!\
_Example: **/clear color list**_

### /edit hex color

Edits a color role with a new name and new HEX color.\
_Example 1: **/edit hex color new\_name:White hex:FFFFFF name:Hotpink**_\
_****Example 1: **/edit hex color new\_name:White hex:FFFFFF number:1**_

### _/edit rgb color_

Edits a color role with a new name and new RGB color.\
_Example 1: **/edit hex color new\_name:White r:255 g:255 b:255 name:Hotpink**_\
_****Example 1: **/edit hex color new\_name:White r:255 g:255 b:255 number:1**_
{% endtab %}

{% tab title="Server settings" %}
### /toggle overlap warning

Toggles the overlap warning on or off.\
_****Example: **/toggle overlap warning**_

### /toggle reaction messages

Toggles the messages when reacting to a color reaction list on or off_**.**_\
_****Example: **/toggle reaction messages**_

### /toggle delete responses

Toggles whether or not to delete the messages Color-Chan sends on or off.\
_****Example: **/toggle delete responses**_

### /toggle join color

Toggles whether or not to give new members a color role.\
_****Example: **/toggle join color**_

### /management roles

Returns a list for color management roles from this server.\
_****Example: **/management roles**_

### /management role

Adds a role to Color-Chan as a color management role.\
_****Example: **/management role role:@mods**_

### /management remove

Removes a color management role from Color-Cha_**n.**_\
_****Example: **/management remove role:@mods**_

### /channel set

Sets a channel in where Color-Chan's commands need to be used in.\
_****Example: **/channel set channel:#bot-chat**_

### /channel remove

Removes the channel restrictions so Color-Chan be used in all text channel again.\
_****Example: **/channel remove channel:#bot-chat**_
{% endtab %}

{% tab title="Misc" %}
### /invite

Returns the invite link for Color-Chan.\
_****Example: **/invite**_

### /vote

Returns the link where you can vote for color-chan.\
_****Example: **/vote**_

### /donate

Returns information about donating to Color-Chan on Patreon.\
_****Example: **/donate**_

### /premium

Returns information about the premium features of Color-Chan.\
_****Example: **/premium**_

### /support

Returns the invite where you can ask for support with color-chan.\
_****Example: **/support**_

### /bot info

Returns some info about Color-Chan. Total servers, member, versions etc.\
_****Example: **/bot info**_

### /patreon info

Returns some info about your patreon subscription.\
_****Example: **/patreon info**_

### /patreon connect

Connect a server with your patreon account.\
_****Example 1: **/patreon connect**_\
_****Example 2: **/patreon connect id:12345**_

### /patreon disconnect

Disconnect a server from your patreon account.\
_****Example 1: **/patreon disconnect**_\
_****Example 2: **/patreon disconnect id:12345**_
{% endtab %}
{% endtabs %}

You can use the _**/help**_ command to see the same list of commands that are listed below.\
Typing **/** will also show all the current slash commands in your server. You can click on Color-Chan's icon to see her commands only.&#x20;

{% embed url="https://cdn.brammys.com/file/brammys/screenshots/2021/12/tF4jDz6ZxESfHIof3SbQzo2cYw0wZ8ZFcNgM2Y4qdKjgEiqX8CPRVSKLMl02uOYJ.png" %}
Color-Chan's command list.
{% endembed %}

Please read the **Slash command issues** page if you can not see any of the slash commands.

{% content-ref url="common-problems/slash-command-issues.md" %}
[slash-command-issues.md](common-problems/slash-command-issues.md)
{% endcontent-ref %}

_****_
