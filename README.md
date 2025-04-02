# MSS-PCB-2024-for-MUR
Main Shutdwon System PCB for FSAE team MUR (Melbourne University Racing). Takes in fault signals (insulation monitoring device, battery management system etc) 
and evaluate fault conditions (brake system plausibility device) via standalone, nonprogrammable analog devices.

First PCB designed and manufactured via reflow soldering, and while all functions worked in testing, problems surfaced when operating continously for long periods of time due to 
lack of proper buffering between signal outputs and relay inputs, leading to component failures when signal ICs weren't able to supply sufficient current. Also recognized the need 
for proper connector placements and pin management, as many of the connections turned out to be unnecessary at the end, leading to messy wiring. 
