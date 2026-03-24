# GHz Hearing

A web-based frequency generator that lets you listen to any frequency from Hz to GHz.

## Features

- **Wide Frequency Range**: 20 Hz to 1 GHz
- **Interactive Slider**: Smooth frequency adjustment
- **Preset Buttons**: Quick access to common frequencies
- **Visual Feedback**: Animated visualizer when playing
- **Web Audio API**: High-quality sine wave generation

## Usage

1. Open `index.html` in a web browser
2. Adjust the slider to select your desired frequency
3. Click "Play" to start the audio
4. Click "Stop" to end playback

## Presets

| Frequency | Description |
|-----------|-------------|
| 20 Hz | Deep bass (below human hearing threshold) |
| 440 Hz | Standard A4 tuning note |
| 1 kHz | Mid-range |
| 10 kHz | High frequency |
| 18 kHz | Upper limit of human hearing |
| 1 MHz | Radio frequency (ultrasonic) |
| 1 GHz | Microwave frequency |

## Deployment

This site is ready for GitHub Pages deployment:

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select "main" branch as source
4. Your site will be available at `https://yourusername.github.io/ghz-hearing/`

## Notes

- Human hearing range is approximately 20 Hz to 20,000 Hz (20 kHz)
- Frequencies above 20 kHz are inaudible to humans but the visualizer shows they're being generated
- Frequencies below 20 Hz are considered infrasound