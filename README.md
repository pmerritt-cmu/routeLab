# NFL Route Simulator

An interactive American football **passing-play simulator** built with **Python** and **cmu_graphics**. The app lets users design offensive formations and receiver routes, simulate plays against defensive coverages, and track basic play statistics like yards gained.

This project is designed as a visual, hands-on way to explore how NFL-style route concepts, coverages, and player interactions work in real time.

---

## Features

* 🏈 **Interactive Field & Players**

  * Quarterback, wide receivers, tight ends, running backs
  * Defensive linemen, linebackers, cornerbacks, safeties

* 📐 **Route & Formation Selection**

  * Choose offensive formations
  * Assign routes to eligible receivers
  * Visual route drawing and execution

* 🛡️ **Defensive Behavior**

  * Man and zone-style coverage logic
  * Pass rush and pursuit behavior

* 🎮 **Game Controls & UI**

  * Clickable buttons for routes, formations, and instructions
  * Start, reset, and stat display controls

* 📊 **Play Statistics**

  * Track total yards gained
  * Basic outcome feedback per play

---

## Technologies Used

* **Python 3**
* **cmu_graphics** (CMU 15-112 graphics library)
* Standard libraries: `math`, `random`

---

## Installation

### 1. Install Python

Make sure Python 3.8+ is installed:

```bash
python --version
```

### 2. Install `cmu_graphics`

```bash
pip install cmu-graphics
```

> Note: `cmu_graphics` works best in a local environment (not browser-based notebooks).

### 3. Download the Project

Clone or download the repository, or ensure you have the main file:

```
nflRouteProjectUpdated.py
```

---

## Running the App

From the project directory, run:

```bash
python nflRouteProjectUpdated.py
```

A new window will open with the football field and UI controls.

---

## How to Use

1. **Select a Formation**

   * Use the formation buttons to align offensive players.

2. **Choose Routes**

   * Assign routes to receivers using the route buttons.

3. **Start the Play**

   * Click the start button to snap the ball and simulate the play.

4. **Watch the Simulation**

   * The quarterback drops back, receivers run routes, defenders react.

5. **View Results**

   * Yards gained and play outcomes are displayed on screen.

6. **Reset & Try Again**

   * Adjust routes or formations and run another play.

---

## Project Structure

* **Player Classes**

  * `Quarterback`, `WideReceiver`, `RunningBack`, `TightEnd`
  * `CornerBack`, `Safety`, `LineBacker`, `DefensiveEnd`, `DefensiveTackle`

* **Gameplay Objects**

  * `Ball`
  * `Zone`

* **UI Components**

  * `Button`, `RouteButton`, `FormationButton`
  * `StartButton`, `StatsButton`, `InstructionButton`

* **Main Loop**

  * Controlled through `runApp()` from `cmu_graphics`

---

## Controls

* **Mouse Clicks** – Interact with buttons and menus
* **On-Screen Instructions** – Explain available actions during gameplay

(No keyboard input required.)

---

## Known Limitations

* Physics and player logic are simplified for visualization
* Defensive AI is rule-based, not predictive
* Best suited for educational or demonstrative use

---

## Future Improvements

* More route combinations and formations
* Enhanced defensive AI and coverage disguises
* Playbook saving/loading
* Improved stat tracking (completions, interceptions, timing)

---

## Author

**Parker Merritt**

---

## License

This project is for educational and personal use. Modify and extend freely.

