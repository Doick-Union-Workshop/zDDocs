# Save/Load Game Menu

This hook is triggered whenever the player changes the savegame slot in the **Save/Load menu**.  
It allows you to run your own script function at that exact moment.  

When a slot is changed, the hook will try to call a Daedalus function named: `MENU_SAVEGAME_API`.

```dae title="Example usage"
func void MENU_SAVEGAME_API()
{
    PrintScreen("Save/load game menu opened!", -1, -1, "FONT_OLD_10_WHITE.TGA", 2);
	Menu_SetItemText("MENUITEM_LOADSAVE_LEVELNAME_VALUE", "Valley of Mines");
};
```
