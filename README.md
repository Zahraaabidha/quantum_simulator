# Quantum Visual Simulator

An interactive web-based quantum simulator that makes qubit behavior visible and intuitive.

---

## What it does

Users apply quantum gates and watch the qubit state evolve in real time across three synchronized visualization modes:

- **Bloch Sphere** — 3D particle shader with a state vector arrow
- **Wave Mode** — probability amplitude as animated 3D bars
- **Phase Plane** — α and β as complex vectors in the complex plane

Gates available: Pauli-X, Hadamard, Pauli-Z, and Measurement.

The physics is accurate — the qubit is modeled using complex amplitudes α and β with correct gate matrix transformations and Born rule measurement statistics.

---

## VR Extension

Built in Unity 6 with XR Interaction Toolkit. Users press physical buttons in an immersive 3D environment to apply quantum gates and observe the Bloch sphere respond in real space.

---

## Tech Stack

- React + TypeScript
- Three.js + React Three Fiber
- Framer Motion
- Google Gemini API
- Unity 6 + XR Interaction Toolkit

---

## Run Locally

1. Install dependencies: `npm install`
2. Add your Gemini API key to `.env.local` as `GEMINI_API_KEY`
3. Run: `npm run dev`

---

## Future Scope

- ESP32 hardware controller with potentiometer knob
- Mobile AR via ARCore
- Multi-qubit entanglement and CNOT gate visualization
