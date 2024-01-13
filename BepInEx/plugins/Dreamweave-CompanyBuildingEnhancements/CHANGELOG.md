## 2.6.0

### Fixed "Sell Scrap From Terminal" Feature

-   "Sell Scrap From Terminal" now works properly in multiplayer lobbies.

-   Items that are in any player's inventory will no longer be taken into account when selling items from the terminal.

-   Updated ReadMe

## 2.5.0

### Quick Bugfix for "Sell Scrap From Terminal"

-   Forgot a single line of code that would remove the green triangles on the radar when using the 'sell' command.

## 2.4.0

### Added one new feature

-   Added 1 new feature: **Sell Scrap From Terminal**
    - Adds a few commands that allow you to sell scrap from the terminal.
    - To use this feature, the ship must be LANDED at the Company Building. </br> </br>
    - Typing "sell scrap" will get you started. It will display a few things on screen: </br> </br>
        - The current company buying rate
        - The amount of scrap items you have in your ship and their combined value at the current company buying rate.
        - The best combination of scrap items you have in your ship required to meet quota and their combined value at the current company buying rate.
        - Two options to sell your scrap items: 'sell' & 'sell all'
        - Typing 'sell' will sell the best combination of scrap items required to meet the quota.
        - Typing 'sell all' will sell all of the scrap on your ship.
        - If you don't care about any of the information on the 'sell scrap' screen, you are welcome to type 'sell' or 'sell all' to skip the info/confirmation window.
        - Like any other feature in this mod you can enable/disable it from the config file, but it is enabled by default as you can simply ignore the terminal commands if you would like.
        - This setting will sync with the host's config file. </br>

-   Updated ReadMe

## 2.3.0

### Added one new feature

-   Added 1 new feature: **Weightless Inventory At Company Building.**
    - This feature is **disabled by default** as it has the potential to function improperly depending on your modlist, although I have worked to make it as compatible with other existing mods as possible. A list of known incompatibilities can be found in the ReadMe.
    - If you experience any incompatibilities that aren't already included in the ReadMe, please disable the feature and let me know in the Discord!
    - If you have BetterStamina enabled in your modlist, this feature will be automatically disabled, regardless of your config setting.

-   Updated ReadMe

## 2.2.0

### Removed one patch from last update.

-   Last update, I made a change that was supposed to fix the following:
    - "Fixed a bug that existed in the base game, where if you quit the game after landing at the company on the final day without turning in your items, and didn't have enough scrap to complete the quota, you would not get fired upon re-entering orbit. (The Automatic Landing feature made this bug much more apparent, but the fix will still be applied if you don't have the setting on.)"

The method I used to fix this bug had a nasty side effect of firing the players before the deadline in certain conditions. For now, i've simply removed the patch. All other patches from the last update should still work fine. I will look for a better way to acomplish this, and hope that eventually the bug is just fixed in the main game.

## 2.1.0

### Performance/Stability Improvements & Bug Fixes

-   The "Automatic Landing" feature has been improved in the following ways:
    - Improved performance.
    - The ship lever now slots into the correct position when Automatic Landing activates.
    - The ship will no longer automatically land when starting up a save file that is already on the final day. It will however be pre-routed to the Company Building when you load up the save.

-   The "Instant Landing" feature has been improved in the following ways:
    - Improved performance
    - Fixed a bug where the instant landing would not correctly sync to clients if they joined the game after the ship was already routed to the Company Building.

-   Fixed a bug that existed in the base game, where if you quit the game after landing at the company on the final day without turning in your items, and didn't have enough scrap to complete the quota, you would not get fired upon re-entering orbit. (The Automatic Landing feature made this bug much more apparent, but the fix will still be applied if you don't have the setting on.)

-   Updated ReadMe

-   A LOT OF CODE WAS CHANGED IN THIS UPDATE, IF YOU HAVE ANY ISSUES PLEASE LET ME KNOW IN THE DISCORD. I do believe it should be all good though, in fact better.

## 2.0.0

### New Feature, Configs, & Config Syncing

-   Added 1 new feature: **Automatic Landing At Company Building When Deadline Reaches 0 Days.**
    - This feature is **disabled by default** as I want to keep the default config file as vanilla as possible. If your goal is to reduce time at the Company as much as possible, this setting is quite nice to have on.

-   Added a config file, so that you may enable/disable specific features of the mod to your liking. The config file will be created automatically after you boot the game for the first time with the mod installed.

-   Settings that affect ship behavior (Instant/Auto Landing) now sync with the host's config file to avoid any desync issues (as long as other players have the mod installed).

-   Updated Icon

-   Updated ReadMe

## 1.0.0

### Initial Upload

-   Instant Landing at Company Building

-   Infinite Stamina/Sprint at Company Building
