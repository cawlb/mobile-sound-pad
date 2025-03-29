# Mobile Sound Pad

A mobile-friendly sound pad application with multi-touch support and visual effects.

## Features

- Simple, clean white grid interface
- Multi-touch support for playing multiple sounds simultaneously
- Sliding/swiping functionality across multiple pads
- Full-screen visual effects that react to sounds
- Different shapes and colors for each sound type
- Visuals overlap when multiple sounds are played

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/cawlb/mobile-sound-pad.git
cd mobile-sound-pad
```

2. Start a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# If you have Node.js
npx serve
```

3. Access the application:
   - On your computer: http://localhost:8000/soundpad.html
   - On your mobile device: http://YOUR_LOCAL_IP:8000/soundpad.html
     (Replace YOUR_LOCAL_IP with your computer's local IP address)

## Controls

- Tap/click on a pad to play a sound
- Slide your finger across multiple pads to trigger sounds in sequence
- Use multiple fingers to play different sounds simultaneously
- Press "Stop All" to stop all sounds
- Toggle "Labels" to show/hide sound names

## Audio Files

Place your WAV audio files in the `sounds` folder to customize the sound pad.

## Customization

You can customize the visual effects by modifying the `visualMappings` array in the JavaScript code. Each sound is assigned a visual mapping that determines its shape, color, and size on the screen.