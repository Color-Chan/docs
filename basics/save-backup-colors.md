---
description: >-
  This article explains everything you should know about how to create backups
  of your color list with the saves commands!
---

# Save/Backup colors

{% hint style="info" %}
You will need to add colors to your list first to use the commands mentioned on this page.\
Information on how to add colors can be found on the **Adding colors** page.
{% endhint %}

{% content-ref url="adding-colors.md" %}
[adding-colors.md](adding-colors.md)
{% endcontent-ref %}

## Saving colors

It is incredibly easy to save colors. All you need to do is use the **/save** command in your server. This will automatically create a full backup of your current color list. A save **ID** is returned after the save has been created. The returned **ID** will need to be used when restoring the save.

## **Restoring saves**

You will need a save ID to restore a save, as mentioned above. The ID needs to be passed to the **/restore save** command. For example: _**/restore save id: 694717296.**_

## Sharing saves

It is possible to share saves with other users of Color-Chan! You can do this with the **/share save** command. For example: _**/share save id: 694717296.**_ This will create a share message in the [official support server](https://colorchan.com/permalinks/support).

{% hint style="info" %}
This command can only be executes in the [official support server](https://colorchan.com/permalinks/support) due to moderation purposes.
{% endhint %}

## _**Viewing previous saves**_

It is possible to view previously created saves with the **/saves** command. This will return a list of saves that currently exist in that server.

<figure><img src="https://cdn.colorchan.com/docImgs/SavesOverview.png" alt=""><figcaption><p>Color list saves overview</p></figcaption></figure>

## Deleting saves

{% hint style="danger" %}
_Deleting saves is **irreversible**. There is no way to restore previously deleted saves!_
{% endhint %}

The delete commands works in the same way as the restore command. Simply provide the corresponding ID of the list you want to **/delete save** to the command. For example _**/delete save id:12345678.**_
