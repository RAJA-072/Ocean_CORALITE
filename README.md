# **Coralite: Ocean Adventure Game**  

![image](https://github.com/user-attachments/assets/ff16de94-ee71-4abe-94b4-2f40acbfc847)

### **Overview**  
*Coralite* is an engaging ocean adventure game developed in Unity inspired by the **SIH1660** problem statement.Players navigate a boat through vast ocean waters, managing fuel levels and direction while being guided by an interactive **Potential Fishing Zone(PFZ)**. The game challenges players to maintain their boat’s performance and find their way through different oceanic routes, fostering both strategic thinking and navigation skills.
The **PFZ** is a service provide by INCOIS whoose importance and awarness can be spreaded by the game.

---

### **Game Features**  

1. **Realistic Boat Controls**  
   - Use intuitive controls to steer the boat left, right, throttle up, and reverse.
   - Smooth rudder and throttle management enhance the gameplay experience.

2. **Fuel Management System**  
   - Fuel consumption decreases as the boat moves, adding a layer of strategy.
   - Players must monitor fuel levels and adjust navigation accordingly.
   - A visual fuel bar and alert system notify players when fuel is low.

3. **Minimap Navigation**  
   - A dynamic minimap tracks the boat’s real-time position in the ocean.
   - The minimap includes an icon that represents the boat’s current location and direction.
   - Players can rely on the minimap for precise navigation across vast ocean environments.

4. **Interactive UI Elements**  
   - **Fuel Bar**: Displays the current fuel level with a color gradient from green (full) to red (low).
   - **Timer**: Tracks game progress and challenges players to manage their time efficiently.
   - **Fuel-Depleted Pop-Up**: An alert appears when the boat runs out of fuel, providing players with visual feedback.

---

### **Controls**  
- **Throttle Up**: Press `Z`  
- **Throttle Down** / **Brake**: Press `S`  
- **Turn Left**: Press `Q`  
- **Turn Right**: Press `D`  
- **Reverse**: Automatic when stopped and pressing `S` with 0 RPM  

---

### **Installation Instructions**  

1. **Download and Open the Project**  
   - Clone or download the *Coralite* project files and open them in Unity.

2. **Scene Setup**  
   - Ensure the main game scene includes the boat GameObject, minimap camera, and UI Canvas for fuel management and navigation.

3. **Assign Script References**  
   - Attach the following scripts to their respective GameObjects:
     - `BoatController`: Controls boat movement.
     - `FuelDisplay`: Manages fuel bar UI and timer.
     - `MinimapController`: Updates the boat’s position on the minimap.

4. **Configure UI Elements**  
   - Assign references for the fuel bar, boat icon, minimap container, and fuel-depleted alert within the Unity Inspector for each respective script.

---

### **How to Play**  

1. **Start the Game**  
   - Navigate through the ocean using boat controls. Monitor fuel consumption to avoid running out.
   
2. **Use the Minimap**  
   - Track your boat’s position and plan routes using the interactive minimap.

3. **Manage Resources**  
   - Keep an eye on the fuel bar and timer to ensure you reach your destination without running out of fuel.

4. **Challenge Yourself**  
   - Strategically balance your speed, direction, and fuel usage to complete various ocean routes and scenarios.

---

### **Future Improvements**  
- **Additional Levels & Challenges**: Introducing new maps, weather conditions, and obstacle courses.
- **Expanded Fuel Management**: Adding fuel stations and refueling mechanics.
- **Leaderboards**: Allowing players to compete for the best time and fuel efficiency.


---
