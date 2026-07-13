# Deep Learning Music Composer

This project is a MIDI-based music composition tool that utilizes a Deep Learning model to generate original musical sequences. It uses an LSTM (Long Short-Term Memory) neural network to learn patterns from a dataset of MIDI files and predict subsequent musical notes and chords.

## Features
* **MIDI Processing**: Uses the music21 library to parse, extract, and normalize musical data from MIDI files.
* **Neural Network**: Implements a stacked LSTM architecture in TensorFlow/Keras to capture long-term temporal dependencies in music.
* **Automated Generation**: Capable of generating new MIDI sequences based on learned patterns.
* **Audio Playback**: Integrated support for playing generated MIDI files directly using pygame.

## Prerequisites
Ensure you have Python installed. You will need to install the following dependencies:

```bash
pip install -r requirements.txt