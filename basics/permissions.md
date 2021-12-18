---
description: >-
  This article explains everything you should know about managing permissions
  for Color-Chan!
---

# Permissions

{% hint style="info" %}
Everyone with the **Manage Roles** permission can **add**, **edit** and **delete color roles** by default. However they can not clear the color list or reaction lists. Users will need to be admin to use those commands, all the **toggle** commands are also admin only.
{% endhint %}

## Color Managers.

You can create one or more **Color Management** roles if you do not want to give users the **Manage Roles** permission. This will make it possible for them to **add**, **edit** and **delete color roles** without **Manage Roles** permission.

### Adding a Color Management role.

{% hint style="info" %}
Adding a Color Management role will deny users with the **Manage Roles** permission from **adding**, **editing** and **deleting color roles** if they do not have the Management role.
{% endhint %}

You can add a management role with the **/management role** command.\
Example: **/management role role:@Admin**

You will be able to view all the management roles with the **/management roles** command once you have added one or more roles.

{% embed url="https://cdn.brammys.com/file/brammys/screenshots/2021/12/6Nc1pBgEGwIw31S1nAIp2IFx6UFCWnSU2DzP8BNW2TPQ5DruIJwcE1ko0ECIc3nu.png" %}
/management roles response.
{% endembed %}

### Removing a Color Management role.

Simply use the **/management remove** command for this. Note: The role has to be on the list returned by the **/management roles** command.\
Example: **/management remove role:@Admin**.
