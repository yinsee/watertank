# Tank Mixer Simulator

A visual 3-tank fluid mixing simulator built with HTML, CSS (Bootstrap 5), and Alpine.js.

## Features

- **3 Source Tanks**: Red, Yellow, and Blue tanks with adjustable levels.
- **Visual Mixing**: Real-time animation of fluid levels and pipe flow.
- **Interactive Controls**: 
  - Start/Stop simulation.
  - Fill individual tanks.
  - Flush the mixed output tank.
- **Dynamic Visuals**:
  - Gradient liquid shading.
  - Bubbling animations.
  - Color-coded pipes that react to simulation state.
  - Spinning turbine animation.
- **Safety Logic**:
  - Auto-stop when source tanks are empty.
  - Auto-stop when mixed tank is full.
  - Warning flashes when tank levels are low.

## Technologies Used

- **HTML5**
- **CSS3** (Custom styles + Bootstrap 5)
- **JavaScript** (Alpine.js for state management)

## How to Run

1. Clone the repository.
2. Open `index.html` in your web browser.
   - OR run a local server (e.g., `python3 -m http.server 8080`) and visit `http://localhost:8080`.
