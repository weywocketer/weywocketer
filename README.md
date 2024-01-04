# My projects
### **FUBAR Ops: Emu War**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/emu.png" width=30%>

Top-down tactical shooter set during the Emu War, made in Unity.
- Player can command individual squad members, change squad formation (with formations like line, wedge and column).
- Friendly and enemy AI:
	- Different steering behaviours, that can be combined (flocking, wander, obstacle avoidance, etc.).
	- State machines controlling unit behaviours.
- Spatial partitioning is utilized to improve performance.
- Terrain map avaliable to the player, with the abiltity to draw on it.
- Different design patterns are utilized to keep the code maintainable.

### *Readme file in the repository contains diagrams and description of the project architecture.*
<br>
Repository: https://github.com/weywocketer/emu-war

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
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/mud.png" width=30%>

Prototype of a platform for the text-based multiplayer game, created using Python.
- Clients can interact with the world by sending player commands to the server.
- In fixed intervals server sends updated world information to clinets.
- Communication based on TCP protocol — due to relatively wide server fixed intervals, higher packet delays are not a big concern.
- Multithreading is used to handle multiple server connections.
- Clients use text-based user interface (TUI) created with npyscreen library.

Repository: https://github.com/weywocketer/mud

---

### **Forresto**
<img src="https://github.com/weywocketer/weywocketer/blob/master/Images/forresto.png" width=30%>

Tower defence made for game jam Ludum Dare 52 in a team of three. Created in Unity.

Game site: https://weywocketer.itch.io/forresto
