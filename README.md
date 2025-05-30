<p align="center">
    <img width="140" src="https://icons.iconarchive.com/icons/iconarchive/red-orb-alphabet/128/Letter-M-icon.png" />  
    <h1 align="center">Hi 👋, I'm MaDHouSe</h1>
    <h3 align="center">A passionate allround developer </h3>    
</p>

<p align="center">
  <a href="https://github.com/MH-Scripts/mh-parkingV2/issues">
    <img src="https://img.shields.io/github/issues/MaDHouSe79/mh-parkingV2"/> 
  </a>
  <a href="https://github.com/MH-Scripts/mh-parkingV2/watchers">
    <img src="https://img.shields.io/github/watchers/MaDHouSe79/mh-parkingV2"/> 
  </a> 
  <a href="https://github.com/MH-Scripts/mh-parkingV2/network/members">
    <img src="https://img.shields.io/github/forks/MaDHouSe79/mh-parkingV2"/> 
  </a>  
  <a href="https://github.com/MH-Scripts/mh-parkingV2/stargazers">
    <img src="https://img.shields.io/github/stars/MaDHouSe79/mh-parkingV2?color=white"/> 
  </a>
  <a href="https://github.com/MH-Scripts/mh-parkingV2/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/MH-Scripts/mh-parkingV2?color=black"/> 
  </a>      
</p>

# My Youtube Channel
- [Subscribe](https://www.youtube.com/@MaDHouSe79) 

# Demo
[![DEMO](https://img.youtube.com/vi/94Syv5NbF54/0.jpg)](https://www.youtube.com/watch?v=94Syv5NbF54)

# MH Parking V2 (QB/ESX) by MaDHouSe79
- Auto park and unpark vehicles
- When you press `F` stort the engine will stop and you can't auto park.
- When you press `F` long then the engine keeps running and it will park the vehicle.
- Before you press `F` use the keys `A` or `D` to turn your wheels, this will save the wheel angle on your parked vehicle.

# Dependencies (QB/ESX)
- [oxmysql](https://github.com/overextended/oxmysql/releases/tag/v1.9.3)
- [ox_lib](https://github.com/overextended/ox_lib/releases)
- [qb-core](https://github.com/qbcore-framework/qb-core) or [esx](https://github.com/esx-framework)
- [qb-policejob](https://github.com/qbcore-framework/qb-policejob) (for qb-core)
- [qb-vehiclekeys](https://github.com/qbcore-framework/qb-vehiclekeys) (for qb-core)
- [mh-vehiclekeyitem](https://github.com/MH-Scripts/mh-vehiclekeyitem)
- [mh-vehicleimages](https://github.com/MH-Scripts/mh-vehicleimages)

# Installation
- Step 1: First stop your server.
- Step 2: Copy the directory `mh-parkinV2` to `resources/[mh]/`.
- Stap 3: Add `ensure [mh]` in `server.cfg` below `ensure [defaultmaps]`.
- Step 4: Start your server.  

# Adding vehicles to the system (QB)
- When a vehicle does not spawn back in, you need to look in `shared/configs/vehicles.lua` and add your vehicles.
- This is a must for modded vehicles you added and are not in default QB
- To get the vehicle hash you can find that with /admin than dev / entity vieuwer, you see a hash number when you aim at an entity and that is what you need,
- or use the command `/gethashkey`, stand next to the vehicle and type `/gethashkey` and you get the hashkey in your F8 console. 
- ESX works with database so you need to add the modded vehicles in esx vehicles table.

# Commands
- `/toggleparktext` Disable or Enable the text above the parked vehicles. (for streamers)
- `/parkmenu` Open the park menu so you can set a waypoint.
- `/addvip [id] [amount]` Add a player as vip (admin only)
- `/removevip [id]` Remove a vip player (admin only)
- `F` press it lock to park and press `F` sort to ignore auto park. 
- `E` to lock vehicles on trailers


# Read Files
[README FILES](https://github.com/MH-Scripts/mh-parkingV2/tree/main/readme)

# Screenshots
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/parked.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer6.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer1.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer2.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer3.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer4.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer5.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer7.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/trailer8.png?raw=true)
![alttext](https://github.com/MH-Scripts/mh-parkingV2/blob/main/screenshots/parkmenu.png?raw=true)

# LICENSE
[GPL LICENSE](./LICENSE)<br />
&copy; [MaDHouSe79](https://www.youtube.com/@MaDHouSe79)
