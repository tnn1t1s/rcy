# RCY

## Background

In the age of AI and rapid software development, the concept of disposable software is becoming more prevalent. Rather than relying on commercial solutions like Propellerhead's ReCycle, which may come with software errors, license key hassles, and limited customization, I've opted to create my own audio slicing tool. This project embodies the idea that sometimes, it's more productive and satisfying to build a tailored solution. By writing my own version:

1. I have complete control over the functionality
2. I can avoid issues with software vendors, license keys, and update cycles
3. I can easily modify and extend the tool as my needs evolve
4. I gain a deeper understanding of the underlying audio processing techniques

This isn't aimed at becoming a large open-source project or a commercial product. It's a personal tool, crafted for my specific needs, showcasing the power of creating disposable, fit-for-purpose software in the AI era.

## About the Tool

This Personal Audio Slicer is a simple GUI application that allows for loading audio files, visualizing the waveform, interactively adjusting split points, and saving the resulting audio segments. It's built using Python with libraries like librosa for audio processing, matplotlib for visualization, and PyQt6 for the user interface.

## Features

- Load and visualize audio waveforms
- Adjust split points using a delta threshold
- Interactive playback of individual segments
- Save split audio segments
