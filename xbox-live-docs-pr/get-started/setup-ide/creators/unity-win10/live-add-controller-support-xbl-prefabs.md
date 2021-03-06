---
title: Adding controller support to Xbox Live prefabs
description: Adding controller support to Xbox Live prefabs using the Xbox Live Unity plug-in.
ms.date: 07/14/2017
ms.topic: article
keywords: xbox live, xbox, games, uwp, windows 10, xbox one, unity, controller support
ms.localizationpriority: medium
---

# Adding controller support to Xbox Live prefabs

> [!IMPORTANT]
> The Xbox Live Unity plugin does not support achievements or online multiplayer and is only recommended for members of the Xbox Live Creators Program; see [Choosing an Xbox Live developer program](../../../join-dev-program/live-dev-program-overview.md).

All of the Xbox Live Unity Plugin Prefabs support specifying controller input in the inspector.

For example, suppose you have a game object called `UserProfile1` which is based on the `UserProfile` prefab.
If you want to tie this game object to Player 1, and have player 1 sign in with the `A` button on their Xbox Controller, write `joystick 1 button 0` in the `Input Controller Button` field in the inspector.

  ![Controller Support in UserProfile Prefab](live-add-controller-support-xbl-prefabs-images/controller-support-example.png)


## All Prefab Controller Input Fields


### UserProfile prefab

- **Input Controller Button:** Adds and signs in an Xbox Live user.


### Social prefab

- **Toggle Filter Controller Button:** Toggles the filter to show either 'All' friends or 'Online' friends.


### Leaderboard prefab

- **First Controller Button:** Takes the player to the first page of leaderboard entries.
- **Last Controller Button:** Takes the player to the last page of leaderboard entries.
- **Next Controller Button:** Takes the player to the next page of leaderboard entries.
- **Prev Controller Button:** Takes the player to the previous page of leaderboard entries.
- **Refresh Controller Button:** Refreshes the leaderboard view.


### Game Save UI prefab

- **Generate New Controller Button:** Generates a new integer save data.
- **Save Data Controller Button:** Saves the current data into the Connected Storage.
- **Load Data Controller Button:** Loads data currently saved in the Connected Storage.
- **Get Info Controller Button:** Retrieves information about saved containers in the Connected Storage.
- **Delete Container Controller Button:** Deletes the saved container from the Connected Storage


## Xbox Controller Button Mappings

For the Xbox Controller Button Mappings in Unity, check out this [Unity Controller Wiki page](https://wiki.unity3d.com/index.php?title=Xbox360Controller).
