# Sea Gauntlet Autonomous Pilot
An autonomous control system developed for the **Sea Gauntlet** game, a simulated environment where a hero ship navigates a lake filled with challenges. This project demonstrates robust decision-making and navigation strategies under dynamic constraints using Unity and C#.  

## 📖 Overview  
The **Sea Gauntlet Autonomous Pilot** project focuses on designing an intelligent agent capable of:  
- Navigating and halting the ship near whirlpools without taking damage.  
- Strategically collecting and alternating between hull and shield power-ups to maintain health and shields.  
- Evading or destroying enemy drones by leveraging environmental features like whirlpools.  
- Neutralizing drone-producing factories to complete mission objectives.  

This project integrates **finite state machines** for dynamic behavior adaptation and demonstrates advanced **AI control algorithms** within a constraint-heavy simulated environment.  

---

## 🎯 Features  
### Navigation  
- **Dynamic Pathfinding:** Safely steers the ship near hazards like whirlpools while avoiding collisions.  
- **Precise Stopping:** Accurately halts the ship at strategic locations for optimal power-up collection.  

### Power-Up Management  
- **Health Restoration:** Collects hull and shield power-ups to recover ship health.  
- **Strategic Switching:** Alternates between power-ups to optimize survivability.  

### Enemy Engagement  
- **Evasion & Attack:** Uses whirlpools to evade enemy drones or destroy them.  
- **Factory Neutralization:** Targets and disables factories to prevent enemy reinforcements.  

---

## 🛠️ Technical Details  
### Control Architecture  
The solution is powered by a **finite state machine** (FSM) that dynamically switches between states based on environmental conditions, including:  
- **Idle State:** Ship waits for the next action.  
- **Navigation State:** Guides the ship to desired waypoints.  
- **Engagement State:** Manages combat strategies against enemies.  
- **Collection State:** Handles power-up acquisition.  

### Tools & Technologies  
- **Unity Engine:** For game environment and simulation.  
- **C#:** For scripting and implementing the autonomous pilot.  
- **AI Algorithms:** Including FSM and dynamic pathfinding for decision-making and navigation.  

---

## 🔧 Setup & Installation  
### Prerequisites  
- Unity (version 2021 or later recommended)  
- Basic knowledge of Unity's editor and C# scripting.  

### Steps to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/mjrzwan/sea-gauntlet-autonomous-pilot.git  
   ```  
2. Open the project in Unity.  
3. Run the `SeaGauntletSimulation` scene to see the autonomous pilot in action.  

### Folder Structure  
```
📂 SeaGauntletAutonomousPilot  
 ┣ 📂 Assets  
 ┃ ┣ 📂 Scripts  
 ┃ ┃ ┣ NavigationController.cs  
 ┃ ┃ ┣ PowerUpManager.cs  
 ┃ ┃ ┗ EnemyEngagement.cs  
 ┃ ┣ 📂 Scenes  
 ┃ ┃ ┗ SeaGauntletSimulation.unity  
 ┃ ┣ 📂 Prefabs  
 ┃ ┗ 📂 Models  
 ┗ 📜 README.md  
```  

---

## 🤝 Collaboration  
Contributions are welcome! If you'd like to contribute:  
1. Fork the repository.  
2. Create a new feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m 'Add feature'`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a pull request.  

---

## 📈 Future Improvements  
- Implement machine learning models to optimize control strategies.  
- Expand environment complexity to include additional hazards and challenges.  
- Add support for multiplayer autonomous agent interactions.  

---

## 🛡️ License  
This project is licensed under the **MIT License**. See the `LICENSE` file for details.  

---

## ✉️ Contact  
For questions, suggestions, or collaboration opportunities, feel free to reach out:  
- **Name:** Mohammed Rizwan 
- **Email:** mjrzwn@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/mjrzwan/

---  