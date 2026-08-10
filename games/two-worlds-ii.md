# Two Worlds II  
=====================  

This page provides a setup reference for running Two Worlds II on modern Windows 10/11 with correct DX10/11 behavior, stable 100 FPS pacing, and proper Grace‑engine configuration. It links to the full installation guide and the recommended Modern Windows pasture configuration for reliable play.

Two Worlds II Best Grazing:  
🐄 Modern Windows Pasture (Windows 10/11)  
(Chosen for correct DX10/11 behavior, stable framerate pacing, and compatibility with ReShade + LSFG.)

~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~

Required Guides  
Two Worlds II — Install Guide  
https://github.com/PitBrat-moo/pasture-of-game-grazing/blob/main/guides/two-worlds-2-install.txt

Pasture Toolshed (wrappers · scaling · shading · MIDI · pacing)  
https://github.com/PitBrat-moo/pasture-of-game-grazing/blob/main/guides/pasture-toolshed.txt

~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~

Notes  
Grace engine requires a strict 100 FPS cap for stable frame pacing.  
HDR is broken; keep `engine.hdr 0`.  
Depth buffer is inaccessible; many ReShade effects will not work.  
Shattered Embrace DLC may require Steam_api.dll replacement.  
PhysX must be installed manually for the HD version.  
Mouse input may break if a controller is attached — disable via `interface.XInputEnable 0`.  
Ultrawide aspect ratios destabilize pacing; prefer 16:9.

⚠️ Stable under Windows 10/11 with RTSS 100 FPS cap  
Avoid framerates above 100; frame pacing becomes unstable.

~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~

Enhancements (Optional)  
Lossless Scaling (LSFG 3.1) for frame generation  
ReShade with the “authentic‑enhanced” preset  
Optional shader cleanup for stability and color accuracy

~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~ ~~

Codex Entry  
Two Worlds II • Modern Windows Pasture
