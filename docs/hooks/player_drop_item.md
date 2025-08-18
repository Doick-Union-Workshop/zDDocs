# Dropping items by player

!!! info "Engine restrictions"
    It's only available for **Gothic 2 Addon (G2A)**!

This hook is triggered whenever the player tries to **drop an item** from his inventory into the game world.  
It lets you control whether an item can be dropped by using a script condition.  

When an item is about to be dropped, the hook checks for a Daedalus function: `C_PlayerCanDropItem`.

```dae title="Example usage"
func int C_PlayerCanDropItem()
{
    if (!Hlp_IsValidItem(item)) { return false; };

    if (Hlp_GetInstanceID(item) == TestBook)
    {
        PrintScreen("You cannot drop this item!", -1, -1, "FONT_OLD_10_WHITE.TGA", 2);
        return false;
    };

    return true;
};
```
