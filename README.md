# drawe!

A browser-based gesture drawing application where you sketch in mid-air using hand gestures through your webcam. Your completed strokes transform into soft, inflatable 3D balloon-like objects that can be manipulated in a shared interactive scene.

---

## ✨ Features

- **Gesture-Based Drawing** – Draw naturally in the air using your index finger.
- **Balloon Inflation** – Completed sketches inflate into soft, floating 3D objects.
- **Real-Time Hand Tracking** – Responsive hand detection powered by MediaPipe Hands.
- **Premium Figma Color Palette** – Create using the official Figma brand colors.
- **Interactive Objects** – Grab, move, rotate, and interact with your balloon creations.
- **Draggable Camera Preview** – Freely reposition the webcam preview anywhere on the screen.
- **3D Scene Navigation** – Orbit, zoom, and explore the scene using mouse controls.
- **Multiplayer Lobby** – Invite a pal and collaborate in real time using lobby codes.
- **Modern Liquid Glass UI** – A sleek interface inspired by Apple's Liquid Glass design language.

---

## 🚀 How It Works

1. **Draw** – Point with your index finger to sketch in the air.
2. **Inflate** – Show an open palm to close and inflate your drawing.
3. **Interact** – Pinch to grab and move balloon objects.
4. **Navigate** – Scroll to zoom, drag to orbit, and click to select.
5. **Clean** – Remove every object from the scene with one click.
6. **Summon** – Invite a pal into your lobby and create together.

---

## 🎮 Controls

```
👉🏻 Point to DRAW | 🤏🏻 Pinch to GRAB | ✋🏻 Palm to BLOW | 🖱️ SCROLL to zoom | 🖱️ DRAG to orbit | 🖱️ CLICK to select
```

---

## 🎨 Color Palette

The application includes the official **Figma Brand Colors**:

- 🟧 Figma Orange — `#F24E1E`
- 🟥 Red Orange — `#FF7262`
- 🟪 Purple — `#A259FF`
- 🟦 Teal — `#1ABCFE`
- 🟩 Green — `#0ACF83`

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/chaith17/drawe.git

# Enter the project directory
cd drawe

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open the local URL displayed in the terminal (typically `http://localhost:5173`).

---

## 📋 Requirements

- Modern browser with WebGL support
  - Google Chrome
  - Microsoft Edge
  - Mozilla Firefox
  - Safari
- Webcam access
- Good lighting for reliable hand tracking
- HTTPS when deployed online (required for camera permissions)

---

## 🛠 Tech Stack

- **TypeScript** — Type-safe development
- **Vite** — Frontend tooling and development server
- **Three.js** — 3D rendering
- **MediaPipe Hands** — Real-time hand tracking
- **GSAP** — Animation engine
- **PeerJS** — Peer-to-peer multiplayer connectivity

---

## 📁 Project Structure

```text
src/
├── main.ts               # Application entry point
├── handTracking.ts       # MediaPipe hand tracking
├── gestureDetector.ts    # Gesture recognition
├── drawingCanvas.ts      # Air drawing renderer
├── scene3D.ts            # Three.js scene
├── objectManager.ts      # Balloon object management
├── balloonInflator.ts    # Converts sketches into 3D balloon meshes
├── handVisualizer.ts     # Webcam hand skeleton overlay
├── multiplayer.ts        # Multiplayer lobby logic
├── constants.ts          # Shared configuration
└── types.ts              # TypeScript definitions
```

---

## 📚 Built With

- Three.js
- MediaPipe Hands
- GSAP
- PeerJS
- Vite
- TypeScript

---

## 👨‍💻 Author

**Chaithanya Pedapudi**

- GitHub: https://github.com/chaith17
- Repository: https://github.com/chaith17/drawe