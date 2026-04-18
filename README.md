# 🛡️ SafePath AI — Smart Safety-Based Route Advisor

SafePath AI is a modern urban navigation prototype that prioritizes **personal safety** over just speed. It uses real-time simulation data, crime hotspots, lighting conditions, and crowd density to recommend the safest possible walking routes.

![SafePath AI Logo](https://raw.githubusercontent.com/placeholder/safepath-logo.png) <!-- Note: Replace with actual hosted logo if available -->

## 🌟 Key Features

### 🗺️ Smart Navigation
- **Safety Scoring**: Routes are ranked by a multi-factor AI logic (Crime + Lighting + Crowd + Time).
- **Route Alternatives**: View up to 3 different walking paths with detailed risk breakdowns.
- **Dynamic Heatmaps**: Toggle a crime hotspot heatmap to visualize high-risk areas.

### 🌓 Dark & Light Mode
- Smoothly toggle between a premium dark glassmorphic theme and a clean, high-visibility light theme.
- Map tiles automatically switch between **CartoDB Dark Matter** and **Voyager**.

### 📱 Emergency SOS (High Impact)
- **One-Click SOS**: Instantly share your live GPS location via a generated Google Maps link.
- **Emergency Alert**: Notify the backend and nearby (simulated) resources with a single click.
- **Voice Guidance**: Automated audio alerts when entering high-risk zones or during emergencies.

### ⏱️ Time-Based Intelligence
- **Risk Timeline**: See how the safety score of a specific route changes across a 24-hour window.
- **Predictive Warnings**: Receive warnings like *"Avoid this route after 9 PM"* or *"Isolated area after midnight"*.

## 🚀 Tech Stack
- **Frontend**: Vanilla JavaScript, HTML5, CSS3 (Custom Grid/Flexbox), Leaflet.js
- **Backend**: Node.js, Express
- **Visuals**: WebGL (Custom Prism Background), SVG Animations, Glassmorphism CSS

## 🛠️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/safepath-ai.git
   cd safepath-ai
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the server**:
   ```bash
   node server.js
   ```

4. **Access the application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure
- `/data`: JSON datasets for crime, lighting, and crowd density.
- `/public`: Frontend assets (HTML, CSS, JS, Prism WebGL).
- `server.js`: Express API for route finding and safety scoring logic.

## 🛡️ License
MIT License - See [LICENSE](LICENSE) for details.

---
*Built with ❤️ for urban safety.*
# safetypath-ai
