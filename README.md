# My projects
### **Anchor**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/anchor5.png" width=31%>   <img src="https://github.com/weywocketer/weywocketer/blob/master/Images/anchor1.png" width=32%>   <img src="https://github.com/weywocketer/weywocketer/blob/master/Images/anchor6.png" width=34%>

A work-in-progress FPP historical sailing simulator, developed in a two-person team, created in Unity. Our main goal is to create a convincing sailing physics simulation, which could be further extended with gameplay features.

Implemented features:
- Apparent wind calculation.
- Calculation of aerodynamic forces (lift, drag) based on sail's angle of attack, sail geometry, wind force; possibility of backing the sail, etc.
- Integration with the ocean simulation from the StormBreakers package (https://github.com/Stormrider31/Storm-Breakers): hydrostatic and hydrodynamic forces on the hull, waves affecting the hull.
- Ship stability and heeling, leeway, weather/lee helm.
- Rudder forces calculation.
- Sails (jib, foresail and gaff mainsail) integrated with Unity Cloth (sail trimming, luffing, etc.).
- Visualization of the running rigging (currently only for sheets) based on Unity Joints.
- Simplified 3D model of an 18th century British cutter, created in Blender.

Features currently in development:
- NavMesh-based on-board movement system (for player and AI crew) — quite a challenge on a constantly moving and rotating multi-storey ship.
- Tweaking simulation parameters to produce realistic ship's behaviour in different weather conditions.
- More detailed cutter model.
- Improved visualization of the running rigging based on catenary equation.

---

### **FUBAR Ops: Emu War**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/emu1.png" width=35%>   <img src="https://github.com/weywocketer/weywocketer/blob/master/Images/emu2.png" width=40%>

Top-down tactical shooter set during the Emu War, made in Unity.
- Player can command individual squad members, change squad formation (with formations like line, wedge and column).
- Friendly and enemy AI:
	- Different steering behaviours, that can be combined (flocking, wander, obstacle avoidance, etc.).
	- State machines controlling unit behaviours.
- Spatial partitioning is utilized to improve performance.
- Terrain map available to the player, with the ability to draw on it.
- Different design patterns are utilized to keep the code maintainable.

### *Readme file in the repository contains diagrams and description of the project architecture.*
<br>
Repository: https://github.com/weywocketer/EmuWar

---

### **Three Red Lines**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/threeRedLines.png" width=30%>   <img src="https://github.com/weywocketer/weywocketer/blob/master/Images/threeRedLines2.png" width=40%>

Side-view 2D/3D RTS game set during the Napoleonic Wars, made in Unity.
- 3 different types of units to command: line infantry, light infantry and militia.
- Distance and melee combat.
- Soldiers in the unit try to maintain the line formation by filling into the empty spots.
- Unit deployment phase before the battle starts.
- Morale and stamina system.
- Unusual, side-view perspective of the battlefield (with 2D sprites fighting in the 3D world).
- 3 scenarios ready to play.
- Simple, random decision based AI.

Game site: https://weywocketer.itch.io/three-red-lines

---

### **2D Submarine physics sim**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/submarine.png" width=30%>

Simple 2D submarine simulation based on the Archimedes' principle, made in Unity.
- No Unity Physics Components were used.
- Simulated with forward Euler method with manual damping.
- Both control planes and ballast tanks can be used to control the ship's depth.

Project site: https://weywocketer.itch.io/2d-submarine-physics-sim

---

### **Multi-User Dungeon game prototype**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/mud.png" width=50%>

Prototype of a platform for the text-based multiplayer game, created using Python.
- Clients can interact with the world by sending player commands to the server.
- In fixed intervals, server sends updated world information to clients.
- Communication based on TCP protocol — due to relatively wide server fixed intervals, higher packet delays are not a big concern.
- Multithreading is used to handle multiple server connections.
- Clients use text-based user interface (TUI) created with npyscreen library.

Repository: https://github.com/weywocketer/mud

---

### **Forresto**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/forresto.png" width=30%>

Tower defence made for Ludum Dare 52 game jam in a team of three. Created in Unity.

Game site: https://weywocketer.itch.io/forresto
