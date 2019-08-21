# **THIS FAQ IS NOT OFFICAL!**
---

## Where do I get the shader?
- You must be a **GOLD** or higher [Patreon](https://www.patreon.com/sonicether/posts) then look for the latest release of [PTGI](https://www.patreon.com/sonicether/posts?tag=Release%20Archives)
---

## What Optifine Do I Need?
- E9 uses [OptiFine 1.14.4 HD U F3](https://optifine.net/downloads) and later
- OptiFine HD U F3 or newer
---

## Any Requirements? (the following is for E9)
- Minecraft 1.14.4 (older version compatibility isn’t possible until new OptiFine features are ported back)
- ### Options > Video Settings
- Details > Alternate Blocks: OFF
- Details > Trees: Fancy or Fast (Smart may break lighting)
- Quality > Natural Textures: OFF
- Shaders > Shadow Quality: 1x
- Shaders > Old Lighting : DEFAULT
- NOTE: Resource packs with custom block models will probably cause  lighting glitches!
---

## What texture packs do people use with PTGI?
- You can find a list by Quavelen on the SEUS Patrons Discord if you are in it you can click [here](https://discordapp.com/channels/354037679131721728/532179479527686154/598337969329537045) to go to the list
---

## Where can I report bugs with PTGI?
- You can report them on the SEUS Patrons Discord if you are in it you can click [here](https://discordapp.com/channels/354037679131721728/574908643947053068) to go to the correct channel
---

## Where can I get help with PTGI?
- You can get help on the SEUS Patrons Discord if you are in it you can click [here](https://discordapp.com/channels/354037679131721728/563294753802682370) to go to the correct channel
---

## Where can I find PTGI develeopment news?
- You can find develeopment news [here](https://www.patreon.com/sonicether/posts?tag=dev%20news) on Sonic Ethers Patreon
---

## What GPUs can I use with PTGI?
### Nvidea
- This is the main GPU type used with PTGI.
### AMD
- Compatibility with AMD GPUs is being actively worked on. You will still experience some minor visual bugs, and you may experience random crashing.
### Intel
- Unfortunately Compatibility is not possible at all.
---

## Known issues with PTGI?
- Block texture alpha is not considered in diffuse GI tracing, so doors and trapdoors don't let any light through their windows currently.
- Being underwater in ravines/caves shows some light leaking, and “glowing” water fog. This is unavoidable currently.
- Some artifacts on edges of water shadows (will improve in the future)
 "Disco Floor" flickering artifact mostly seen in reflections (the new Secondary GI Samples option can help with this)
- Secondary GI bounces (2nd bounce and onward) can take a while to adapt to lighting changes
- Blocks which are not a full-sized cube in the world aren't considered properly in lighting and reflections (causes artifacts with half slabs, stairs, and the like)
- Issues with the rendering of semi-transparent/translucent materials
