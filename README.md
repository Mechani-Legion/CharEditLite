# CharEditLite
Mod for Conan Exiles

A little mod for saving, loading or editing the appearance of the characters and thralls (for solo/coop and server).


## Summary & manual

**Features:**
- Full character editor.
- Customisation rights management for admin.
- HD preview with free camera to look around it.
- Toggle off/on the outfit of the previewed character.
- Percentage display for scalar sliders and possibility to set them manually.
- Management of appearances with code and shards.
- Full RGB color choice for shard creation.
- The thralls can be changed with shards.
- Checking and auto-correction of the edited character.
- Test Lab for experimental features (RGB for character).
- Good compatibility with others mods. Automatic addition of their customisation features.

**Complementary info:**
- Mod ID: 1366358141
- Solo/coop and server compliant.
- The mod is triggered by an item named "Mirror". Crafted at Artisan's Worktable.
- The mirror gives a code or can create an item named "Shard" for the management of appearances.
- Admin can set the customisations available for the mirror and fragments.
- Admin can use black/white list to manage players access to the mirror and shards.
- The shard can be used on self for a quick change of appearance.
- The shard must be placed in thralls inventory/station and then used to change them.
- The shard can capture the target appearance.
- The shard can edit its stored appearance when placed in the character inventory.
- The shard show available customisations and can select which one to use.
- In case of religion changing. If you want to update the recipes, you need to use a yellow lotus potion.
- Auto-correction is based on vanilla values, but they can be altered by others mods.
- Scalars values can be chosen between vanilla and modded.
- Old generated code can be invalidated by game update.

**How to be Admin:**
- Esc menu in game => "Settings" => tab "Server Settings" => click "Make Me Admin" => Exit settings
- Esc menu in game => "Admin Panel"

**Overview/editor panel: Contains all the modifiable informations of the character.**
- Button "Regenerate code":
  - Get the code of the in game character and displays its informations and preview.
  - Can be used in case of invalid code.
- Code field: Can contain the code of the in game character or mirror character or notepad/txt character.
  - The code can be copied from the field to notepad/txt, and vice versa.
  - Manually set code: If valid, its informations and preview are displayed.
  - Using editor: Checking values and update code.
- Button "Create shard":
  - Put a shard in the inventory with the appearance of the preview stored on it.
  - Shard can be created with different appearances without using the button "Apply" of the mirror.

**Preview panel: Render of the in game character or the edited one.**
- Mouse:
  - Left click to move and rotate.
  - Wheel to zoom.
- Button "Reset":
  - Resets camera view.
  - In case of invalid code, get the code of the previewed character instead of the in game character.

**Shard panel: Render of the shard or target appearance and of the final appearance according to the choices.**
- Interaction: Same as the mirror.
- Upper checkbox: Only for station thralls, the warpaint and outfit of the shard can be apply to them. The appearance of the shard can also be ignored in these cases.
- Lower checkbox: Enable or disable the customisation option if available.
- Edit mod: Only available in the character inventory.
  - Switch warpainnt: Change the warpaint according to the character.
  - Switch outfit: Change the outfit according to the character.

**Admin panel: Show general access for all mirrors and shards. Also show player list for specific access.**
- Checkbox: Enable or disable the customisation option.
- Button "Commit": Needed to save all changes made.
- List: Show the identified players.
  - Buttons: Manage specific access for a selected player.
  - Delete all: Erase all lists and can not be cancelled, players need to relog to refresh the lists.

**Checking & message:**
- Request confirmation triggered before changing the in game character by the mirror or shard character.
- In case of invalid code:
  - The interface is greyed.
  - "Regenerate code" and "Reset" still available to reget a code.
- In case of wrong values (mostly with gender change):
  - The auto-correction changes it or them.
  - Notification of warning triggered.

**Know issues:**
- Buildings name don't change when players define their new name. Log out/in is requiered to refresh buildings name. Properties still belong to players even without refreshing the name.
- Hair of the previewed character may be degrade to low quality. It's a temporary glitch, the code and in game character still correct when you apply modifications.
- A seam may be visible on the neck of the previewed character. It's a temporary glitch, the code and in game character still correct when you apply modifications.
- Some scalars can render a wrong preview. The code still correct and the in game character is modified according to it.
- Some scalars are ignored by station thralls, but the fragment remains valid and can be applied correctly to characters and placeable thralls.
- Some issues can occur with the order of the mods. Try placing this mod at the top or bottom of the list to fix this.
