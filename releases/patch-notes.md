---
description: All the release notes for Color-Chan's version can be found here.
---

# Patch notes

## v4.10.0 - August 15 2022&#x20;

* Added `Pastel`, `Random` and `Original` default color lists.
* Added better message formatting with lists of color names and errors.

## v4.9.0 - August 07 2022&#x20;

* Added the `delete-role` option to the `/delete color` command.

## v4.8.9 - July 22 2022

* Removed the restriction on color management roles so managed roles (roles from integrations) can be added as management roles.

## v4.8.8 - July 20 2022

* Added 2 more colors to the default color list.
* Removed vote lock from `/add default colors`.

## v4.8.7 - July 04 2022

* Fix: Sending color removed message even when the reaction replies have been disabled.

## v4.8.6 - June 24 2022

* Added better error message when reaction list is missing in the database.
* Updated dependencies.

## v4.8.5 - June 23 2022

* Added a delay when updating color reaction messages to avoid a race condition with discord.

## v4.8.4 - June 16 2022

* Added docs link to color overlap error message.

## v4.8.3 - June 13 2022

* Added SEO header tags to the website for better search engine indexing.

## v4.8.2 - June 12 2022

* Fixed border on the header on page load.

## v4.8.1 - June 10 2022

* Decreased the website page sizes by 50%.

## v4.8.0 - June 08 2022

* Increased the default color reaction limit from 16 to 20.
* Fixed incorrect home page title.

## v4.7.0 - June 06 2022

* Added a new website.
* Updated all dependencies.

## v4.6.12 - May 31 2022

* Updated all dependencies.

## v4.6.11 - May 03 2022

* Updated all dependencies.

## v4.6.10 - April 11 2022

* Updated all dependencies.

## v4.6.9 - March 15 2022

* Added a Redis server to handle all the caching.

## v4.6.8 - March 13 2022

* Moved the Discord proxy to Color-Chan's kubernetes cluster.

## v4.6.7 - March 11 2022

* Added retries for uploading images to S3.

## v4.6.6 - March 7 2022

* Added some very secret dev commands to help with debugging.

## v4.6.5 - March 5 2022

* Fix: Typo in help command.

## v4.6.4 - March 2 2022

* Fix: Unable to export color lists for some servers.

## v4.6.3 - February 18 2022

* Added support for more emojis on the color list.
* Added more random colors.
* Updated all dependencies.

## v4.6.2 - January 28 2022

* Updated all dependencies

## v4.6.1 - January 17 2022

* Updated all dependencies

## v4.6.0 - January 11 2022

* Added the **/toggle export command** command, so you can turn the export feature on or off for your server!
* Fix: Not deleting management roles if they have been deleted.
* Fix: The **/update color list** command used the reversed order of the role order in the server settings.

## v4.5.1 - January 5 2022

* Updated all dependencies

## v4.5.0 - December 28 2021

* Added confirm message for **/clear color list**.
* Added confirm message for **/clear reaction lists**.
* Fix: Typo in audit log reasons.
* Updated all dependencies.
