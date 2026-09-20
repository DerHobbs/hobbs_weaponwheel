# hobbs_weaponwheel

Colorful Weapon Icons, RedM standalone.

RDR2 draws every icon in the weapon wheel in plain white, so at a glance one revolver looks like the next one. This resource swaps those icons for colored ones. Drop it in, start it, done.

No dependencies, no framework, no edits to your RDR2 installation.

## Screenshots

<img width="924" height="947" alt="Screenshot 2026-09-20 175321" src="https://github.com/user-attachments/assets/c8bec914-db6a-47f2-b53a-df64674e3916" />
<img width="907" height="1056" alt="Screenshot 2026-09-20 175327" src="https://github.com/user-attachments/assets/ede38b21-7c2d-4c0a-a502-8afd263c96b4" />

## Install

1. Download the resource. Either use the green **Code** button and **Download ZIP**, or clone it:
   ```
   git clone https://github.com/DerHobbs/hobbs_weaponwheel
   ```
2. Put the folder `hobbs_weaponwheel` into your `resources` folder.
3. Add one line to your `server.cfg`:
   ```
   ensure hobbs_weaponwheel
   ```
4. Restart the server.

Your players get the icons the next time they join. They do not have to install anything.

## What is inside

| File | What it covers |
| --- | --- |
| `stream/multiwheel_weapons.ytd` | The 99 icons on the weapons tab of the wheel |
| `stream/inventory_items.ytd` | The icons on the items tab, also used by satchel and stores |

## Good to know

* Only one resource on a server can ship these files. If another resource streams the same file name, the one that starts last wins, so pick one and remove the other.
* Nothing is written to your RDR2 folder. The files are streamed at runtime, so single player and other servers stay untouched.
* Works next to VORP, RSG and standalone setups alike, because this resource is only textures.

## Credits
Icons by DerHobbs. Base textures by Rockstar Games.

## License

[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/)

Use it on any server you like and pass it on, as long as you keep the credit. Do not publish a changed version of it. If you want something added or fixed, open an issue here instead.
