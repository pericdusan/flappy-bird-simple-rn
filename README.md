# Flappy Bird React Native

A simple and fun Flappy Bird clone built using React Native and [Expo](https://expo.dev/). The game implements custom physics and game logic using pure React Native hooks (`useState` and `useEffect`) without any external game engine dependencies.

## 📱 Preview

<p align="center">
   <img width="300" alt="image190" src="https://github.com/user-attachments/assets/eea71cf7-eae4-4219-a9d2-566f352659f0" />
   <img width="300" alt="image189" src="https://github.com/user-attachments/assets/5752c1fe-d30f-416b-9c16-b70333fef853" />
</p>

## 🌟 Features

- **Custom Game Engine**: Built entirely with React Native state and timers (`setInterval`).
- **Physics**: Simulated gravity and jump mechanics.
- **Collision Detection**: Real-time collision detection between the bird and moving obstacles (pipes).
- **Infinite Gameplay**: Procedurally generated, continuously moving obstacles.
- **Score Tracking**: Automatic score calculation as you successfully pass through pipes.

## 🚀 Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your computer.
- Expo Go app installed on your smartphone (for testing on a physical device) or an iOS/Android emulator configured on your machine.

### Installation

1. Clone the repository (if you haven't already):
   ```bash
   git clone https://github.com/DusanPeric44/flappy-bird-rn.git
   ```
2. Navigate into the project directory:
   ```bash
   cd flappy-bird-rn
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the App

Start the Expo development server:

```bash
npm start
```

Once the development server is running, you can:
- **Scan the QR Code**: Open the Expo Go app on your mobile device and scan the QR code displayed in your terminal.
- **Run on Emulator**: Press `a` to open the app on an active Android emulator, or `i` to open it on an iOS simulator.

## 📁 Project Structure

- `App.js`: The main entry point containing the game loop, state management, collision detection, and game layout.
- `src/components/Bird.js`: Component rendering the player character (Bird).
- `src/components/Obstacle.js`: Component rendering the moving pipes/obstacles.
- `assets/`: Contains game image assets like the background.

## 🛠 Built With

- [React Native](https://reactnative.dev/) - A framework for building native apps using React.
- [Expo](https://expo.dev/) - A platform for making universal native apps with React.
