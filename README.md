# MIDI Metrist

![Application Screenshot](screenshot.png)


A specialized tool for analyzing rhythmic and dynamic evenness in piano scales. It is specifically designed to evaluate MIDI recordings of single-note patterns (such as quarter-note scales) played against a steady beat.

Unlike general MIDI timing tools, this analyzer focuses on the micro-consistency of technical execution, helping pianists identify finger-specific weaknesses and directional biases.

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

1. **Record your MIDI**: Record a technical exercise (like a C Major scale) against a steady metronome. The tool is optimized for **quarter-note** recordings.
2. **Select Hand**: Toggle between **Left Hand (LH)** and **Right Hand (RH)** in the tool.
3. **Upload**: Drag and drop your `.mid` file into the analyzer. You can use the included `example.mid` to test the functionality immediately!
4. **Analyze**: Explore the dashboard, charts, and tables to identify technical areas for improvement.

## 🛠️ Technical Stack

- **Core**: Vanilla JavaScript (HTML5/CSS3)
- **MIDI Parsing**: [@tonejs/midi](https://github.com/Tonejs/Midi)
- **Visualization**: [Chart.js](https://www.chartjs.org/)
- **Styling**: Modern CSS with Glassmorphism and CSS Grid/Flexbox

## 📥 Installation

This is a portable, single-file web application. No installation is required.

1. Clone the repository or simple download the `index.html` file.
2. Open `index.html` in any modern web browser.
3. Use the included `example.mid` to see an example analysis.

---
*Created for musicians looking to perfect their technical precision through data-driven practice.*
