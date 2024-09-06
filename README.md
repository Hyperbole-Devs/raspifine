# Description
RaspiFine is a free, lightweight optimization modpack specially made to be run on Raspberry Pis. It consists of the best configs and mods specially optimized for users playing Minecraft on the Raspberry Pi. RaspiFine also includes some carefully chosen Quality-Of-Life mods, to balance the Optimization/Quality scale.

![This modpack is available on Modrinth.](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/cozy/available/modrinth_vector.svg)

![This modpack is available for the Fabric modloader.](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/compact/supported/fabric_vector.svg)     ![This modpack is available for the Quilt modloader.](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/compact/supported/quilt_vector.svg)

# What Can RaspiFine Help With?
RaspiFine optimizes and finetunes different areas of gameplay. They include:
- Reducing lag & improving framerate.
- Reducing CPU & GPU usage spikes (micro-stuttering).
- Improving server ping & response time.
- Making game boot times quicker.
- Making singleplayer worlds load faster.
- Culling entites & objects that can't be seen.
- Speeding up rendering in gameplay.
- Changing the game resolution.
- Decreasing memory usage.

# When Should I Use RaspiFine?
You should use RaspiFine on your Raspberry Pi if:
- Minecraft is generally laggy and difficult to play.
- Your CPU & GPU usage spikes frequenly during gameplay (micro-stuttering).
- Your ping on servers is not playable, and you see teleporting players.
- It takes a interminable (very long) amount of time to boot Minecraft.

# How Much Of A Difference Does RaspiFine Make?
Here's some screenshots to show you the difference:

## Vanilla
- Singleplayer FPS:
![Average singleplayer fps when standing still for two minutes.](https://cdn.modrinth.com/data/cached_images/7bea14968f78ce4c617550c345b39171b7700fa3.png)
- Multiplayer FPS:
![Average vanilla multiplayer fps when standing still for two minutes.](https://cdn.modrinth.com/data/cached_images/2a661cb61901f5d6b64f9fb457f6a3c69bf6a6e2.png)

## Simply Optimized
- Singleplayer FPS:
![Average singleplayer fps for Simply Optimized modpack.](https://cdn.modrinth.com/data/cached_images/32c482a461faad97b0b1410263bc5135f455990d.png)

- Multiplayer FPS:
![Average multiplayer fps for Simply Optimized modpack.](https://cdn.modrinth.com/data/cached_images/ab6df62c0a6292a2d12ae1d06f70512407c0bc9a.png)

## RaspiFine
- Singleplayer FPS:
![Average singleplayer fps using RaspiFine](https://cdn.modrinth.com/data/cached_images/25d76b42c8cdfb819cf62c5bb32d20f75e2d3451.png)

- Multiplayer FPS:
![Average multiplayer fps using RaspiFine modpack.](https://cdn.modrinth.com/data/cached_images/21c7b239ff9d96075d41ceb270e80e164aec6b66.png)

**PLEASE NOTE THAT THIS WAS TESTED ON A RASPBERRY PI 5 IN 720P RESOLOUTION WITH THE CPU OVERCLOCKED TO ~~2.6GHZ~~ 2.8GHZ. DEPENDING ON YOUR MODEL & THE SILICON LOTTERY, YOUR RESULTS MAY VARY. WE DO NOT GURANTEE THAT YOU WILL REACH THE HIGHLIGHTED FRAMERATE, BUT YOU SHOULD USE THIS AS A ROUGH ESTIMATE.**

# Is My Raspberry Pi Powerful Enough To Run RaspiFine?
We recommend running RaspiFine on the Raspberry Pi 4 or later, otherwise they may not run stably/and or may have the incorrect GPU drivers to run Minecraft.
You can see if you Raspberry Pi is powerful enough to run RaspiFine below:

### Recommended To Be Ran On:
- [Raspberry Pi 5 Model B](https://datasheets.raspberrypi.com/rpi5/raspberry-pi-5-product-brief.pdf)
- [Raspberry Pi 4 Model B](https://datasheets.raspberrypi.com/rpi4/raspberry-pi-4-product-brief.pdf)

### Can Still Be Run On, Not Guranteed For Stability:
- [Raspberry Pi 3 Model B+](https://datasheets.raspberrypi.com/rpi3/raspberry-pi-3-b-plus-product-brief.pdf)
- Raspberry Pi 3 Model B
- [Raspberry Pi 3 Model A+](https://datasheets.raspberrypi.com/rpi3/raspberry-pi-3-a-plus-product-brief.pdf)
- [Raspberry Pi 400](https://datasheets.raspberrypi.com/rpi400/raspberry-pi-400-product-brief.pdf)

### Cannot Be Ran On:
- Raspberry Pi 2 Model B
- Raspberry Pi 1 Model B+
- Raspberry Pi 1 Model A+

# Mods
Here are the mods preloaded in the lastest stable version of RaspiFine:

<details>
<summary>Optimization Mods</summary>

## Optimization Mods
- Sodium - jellysquid3
- Lithium - jellysquid3, 2No2Name
- ResolutionControl+ - juliand665, UltimateBoomer, fantahund
- Krypton - tuxed
- ImmediatelyFast - RK_01
- EntityCulling - tr2zw
- Sodium Extra - FlashyReese
- Memory Leak Fix - FX
- RailOptimizations - FX
- FerriteCore - malte0811

</details>


<details>
<summary>Quality-Of-Life Mods</summary>

## Quality-Of-Life Mods
- Better Ping Display - Quintinity
- Better F3 - cominixo, TreyRuffy
- Mod Menu - Prospector, haykam921, modmuss50, TerraformersMC
- Reese's Sodium Options - FlashyReese
- Replay Mod - CrushedPixel, johni0702
- Zoomify - isxander
- FancyMenu - Keksuccino
- FancyMenu SIA - Keksuccino
- FPS Display - Grayray75
- Better Statistics Screen - TheCSDev
- Xaero's Minimap - xaero96
- Item Highlighter - Grend
- Language Reload - Jerozgen

</details>


<details>
<summary>Mod Libraries</summary>

## Mod Libraries
- Fabric API - modmuss50
- Cloth Config API - shedaniel
- YetAnotherConfigLab - isxander
- Konkrete - Keksuccino
- Melody - Keksuccino
- Fabric Language Kotlin - modmuss50
- Iceberg - Grend
- Forge Config API Port - Fuzs
- Quilted Fabric API (QFAPI) / Quilt Standard Libraries (QSL) - Quilt-Holdings

</details>

# Configuration Options
Here are the configuration options preloaded in the latest stable version of RaspiFine:

## General
- Render Distance: 6
- Simulation Distance: 6
- Brightness: 65%
- GUI Scale: 2x
- Fullscreen - OFF
- VSync: ON
- Max Framerate: Unlimited
- View Bobbing: ON
- Attack Indicator: Crosshair
- Autosave Indicator: OFF

## Quality
- Graphics: Fancy
- Clouds: OFF
- Weather: Fast
- Leaves: Fancy
- Particles: Minimal
- Smooth Lighting: ON
- Biome Blend: 1 Block
- Entity Distance: 75%
- Entity Shadows: OFF
- Vignette: OFF
- Distortion Effects: 100%
- FOV Effects: 100%
- Mipmap Levels: 2x

## Animations
- Water: ON
- Lava: ON
- Fire: ON
- Nether Portal: ON
- Block Animations: ON
- Sculk Sensor: ON

## Details
- Sky: ON
- Stars: ON
- Sun & Moon: ON
- Weather: ON
- Biome Colors: ON
- Sky Colors: On

# Server Compatibility
Currently, RaspiFine is not compatible with the server version of Minecraft. We hope to bring this to you in a seperate modpack in the future. If you need to run a Minecraft server on your Raspberry Pi now, I highly recommend checking out [Simply Optimized](https://modrinth.com/modpack/sop) by HyperSoop as their modpack includes similar optimizations and is compatible with

# Thanks
A big shoutout to the mod developers that this modpack consists of, as they work so hard to keep Modrinth running :).
