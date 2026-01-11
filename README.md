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

## Installation

### 1. Install Python

### 2. Install `cmu_graphics`

> Note: `cmu_graphics` works best in a local environment (not browser-based notebooks).

---

## How to Use

1. **Select a Formation**

   * Use the formation buttons to align offensive players.

2. **Choose Routes**

   * Assign routes to receivers using the route buttons.

3. **Start the Play**

   * Click the start button to snap the ball and simulate the play.

4. **Be the QB**

   * Throw the ball to your receivers.

5. **View Results**

   * Yards gained and play outcomes are displayed on screen.

6. **Reset & Try Again**

   * Adjust routes or formations and run another play.

---

## Project Structure

* **Player Classes**

  * `Quarterback`, `WideReceiver`, `RunningBack`, `TightEnd`
  * `CornerBack`, `Safety`, `LineBacker`, `DefensiveEnd`, `DefensiveTackle`

* **UI Components**

  * `Button`, `RouteButton`, `FormationButton`
  * `StartButton`, `StatsButton`, `InstructionButton`

* **Event Handlers**

## Authors

* Parker Merritt: [pmerritt@andrew.cmu.edu](mailto:jryman@andrew.cmu.edu)
* James Ryman: [jryman@andrew.cmu.edu](mailto:jryman@andrew.cmu.edu)

##
