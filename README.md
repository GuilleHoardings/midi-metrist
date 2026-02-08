# MIDI Piano Practice Analyzer

A premium web-based tool designed to analyze piano scale recordings and provide deep technical insights into timing, velocity, and fingering technique.

## 🎹 Key Features

### 1. Performance Dashboard
- **Average Velocity & Jitter**: Monitor your dynamic control and range.
- **Timing Accuracy**: View average millisecond offset from the rhythmic grid.
- **Consistency Score**: Statistical standard deviation of your timing.
- **Deviation Tracking**: Automatic flagging of notes with significant timing or velocity errors.

### 2. Interactive Piano Visualization
- **Scale Mapping**: Visualizes your performance on a virtual 88-key piano.
- **Directional Analysis**: Separate visualizations for ascending and descending scale patterns.
- **Crossing Detection**: Automatically identifies finger crossings (thumb-under/finger-over) and highlights them with motion indicators.

### 3. Finger-Note Distribution Analysis
- **Pitch-Specific Data**: Distinguishes between octaves (e.g., C4 vs C5) to isolate range-specific technical weaknesses.
- **Directional Split**: Separate charts for ascending and descending movements to catch directional bias.
- **Early/Late Bias**: Instead of simple averages, it shows **Average Late (+)** and **Average Early (-)** offsets separately for every finger-note combination.
- **Velocity Tracking**: Overlay line chart showing average velocity per finger.

### 4. Technical Insights
- **Heuristic Fingering**: Intelligent algorithm that maps your performance to standard scale fingerings (Right Hand/Left Hand configurable).
- **Rhythmic Feedback**: Detailed insight into whether you tend to play ahead or behind the beat.
- **Dynamic Heatmap**: Highlights dynamic consistency across different fingers.

## 🚀 How to Use

1. **Record your MIDI**: Record a scale (recommended: quarter notes) in any MIDI sequencer.
2. **Select Hand**: Toggle between **Left Hand (LH)** and **Right Hand (RH)** in the tool.
3. **Upload**: Drag and drop your `.mid` file into the analyzer.
4. **Analyze**: Explore the dashboard, charts, and tables to identify technical areas for improvement.

## 🛠️ Technical Stack

- **Core**: Vanilla JavaScript (HTML5/CSS3)
- **MIDI Parsing**: [@tonejs/midi](https://github.com/Tonejs/Midi)
- **Visualization**: [Chart.js](https://www.chartjs.org/)
- **Styling**: Modern CSS with Glassmorphism and CSS Grid/Flexbox

## 📥 Installation

This is a portable, single-file web application. No installation is required.

1. Clone the repository.
2. Open `index.html` in any modern web browser.

---
*Created for musicians looking to perfect their technical precision through data-driven practice.*
