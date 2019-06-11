# Tsunami's Minimal Apex Legends Config

**__As of patch 1.2, most config commands received an extra, unintentional flag. As a result, this config currently won't achieve much. It is a [known issue](https://www.reddit.com/r/apexlegends/comments/bxbaer/known_issues_post_patch_12/) and will be addressed soon. A *potential* workaround might be setting a videoconfig with equivalent settings, but this has yet to be confirmed.__**

## Which configs should I use?
* hudtweaks.cfg - This introduces some HUD changes, such as transparent HUD backgrounds, rotating minimap, semi-transparent pings, and grenade/health to activate on press from wheels. These are purely preference and offer no FPS gains. **Recommended**
* occlusion.cfg - This config disables sound occlusion, reducing the blocking of noise when there are objects or entities between you and the sound source. **Recommended**
* toaster.cfg - This config will make your game look worse with a trade-off of higher FPS. Use this if you need more frames. **Recommended**

## How to Use
1. To download the scripts, click the green 'Clone or Download' button, and then click 'Download ZIP'.
2. Drop autoexec.cfg into Apex Legend's cfg folder (Typically located at `C:\Program Files (x86)\Origin Games\Apex\cfg`)
3. If you choose to use any of the additional configs, you **must** create a folder named `addons` in your cfg folder.
4. If using any additional configs, drop them in the `addons` folder.
5. Add `+exec autoexec` to your launch options (Access this by hitting the gear cog in Origin for Apex and then going to Game Properties->Advanced Launch Options)

## Important Notes
1. If you use `toggleads.cfg`, because +speed is also used for toggling variable scopes, it will change the zoom level as you begin to sprint. This is a drawback to the current script. If you want to change this behavior, you can change lines 9 and 10 to:
`alias "+anu_sprint" "-zoom; alias adstoggle startzoom"
alias "-anu_sprint" "+speed; -speed"`
This will make you sprint by letting go of the key instead.
2. If you use `toggleads.cfg`, it will override your current r, lshift and mouse2 binds.
3. To reset settings, you will either have to flip the values back to their defaults and relaunch, or reinstall the game. In the near future I will provide a config that does just this.

## Donations
[If you want to buy me a cup of coffee, I would greatly appreciate it!](https://www.paypal.me/TsuBTW)

## Questions? Suggestions?
[Join us on Discord](https://discord.gg/2HgNzD9).
