# Hand Gesture Controlled Game

A Python-based interactive game that uses computer vision to detect hand gestures for control, creating an immersive gaming experience.

## Features
- Real-time hand gesture recognition using OpenCV and MediaPipe
- Multiple game levels with progressive difficulty
- Customizable ball colors and background music
- High score tracking system
- Dynamic obstacle generation
- Lives and level system

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)
- Pygame (`pygame`)
- NumPy (`numpy`)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/DANI-cloud-del/Python-Hand-Gesture-Game.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Controls
- **Thumbs Up**: Move character upward
- **Thumbs Down**: Move character downward
- **Index Finger Right**: Move character right
- **Index Finger Left**: Move character left
- Press 'Q' to quit the game

## Gameplay
- Avoid red obstacles
- Score increases with survival time
- Game difficulty increases every 50 points
- Limited lives - make them count!
- Track your high score

## Sound Files
- `background_music.wav`: Main game music
- `background_music2.wav`: Alternative background track
- `background_music3.wav`: Menu music
- `background_music_4.wav`: Game over music
- `icon_change_sound.wav`: UI interaction sound

## Development
- Written in Python 3
- Uses OpenCV for camera input
- MediaPipe for hand tracking
- Pygame for game graphics and sound

## License
MIT License
