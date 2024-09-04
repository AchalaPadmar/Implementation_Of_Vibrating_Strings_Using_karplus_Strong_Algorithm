# Implementation Of Vibrating Strings Using karplus Strong Algorithm

This project is a Python-based synthesizer that simulates the sound of vibrating strings using the **Karplus-Strong** algorithm. The application allows you to play individual notes, predefined melodies, and visualize the waveform, spectrogram, and FFT of the generated sounds in real-time.

##  Features

- **Real-Time Note Playing**: Play individual notes corresponding to the keys `c`, `d`, `e`, `f`, `g`, `a`, `b` in the 4th octave.
- **Predefined Melodies**: Play classic melodies like "Happy Birthday" and "Twinkle Twinkle Little Star".
- **Chord Sequences**: Replay all notes played during the session or play all notes sequentially.
- **Real-Time Visualization**: Generate and display waveform, spectrogram, and FFT plots for the notes and melodies in real-time.

##  Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/karplus-strong-guitar-synthesizer.git
   cd karplus-strong-guitar-synthesizer
   ```

2. **Install Dependencies**
   Ensure you have Python 3.7+ and install the required libraries:
   - `numpy`
   - `sounddevice`
   - `matplotlib`
   - `scipy`
   - `pynput`
   
   Install dependencies using pip:
   ```bash
   pip install numpy sounddevice matplotlib scipy pynput
   ```

##  Usage

1. **Run the Synthesizer**
   ```bash
   python main.py
   ```

2. **Keyboard Controls**
   - `c`, `d`, `e`, `f`, `g`, `a`, `b` — Play corresponding notes in the 4th octave.
   - `x` — Play the "Happy Birthday" melody.
   - `y` — Play the "Twinkle Twinkle Little Star" melody.
   - `z` — Play all notes from C4 to G5 sequentially.
   - `w` — Replay all notes played in the current session.
   - `q` — Quit the application.

3. **Visualizations**
   - After playing a note or melody, the waveform, spectrogram, and FFT of the generated sound will be displayed in separate plots.

##  Examples

### Playing Individual Notes
Pressing the `c` key will play the C4 note and show the following visualizations:

- **Waveform**: Displays the time-domain signal of the note.
- **Spectrogram**: Shows the frequency content of the note over time.
- **FFT**: Displays the frequency-domain representation of the note.

### Predefined Melodies
- **Happy Birthday**: Press `x` to play the "Happy Birthday" melody.
- **Twinkle Twinkle Little Star**: Press `y` to play "Twinkle Twinkle Little Star".

### Chord Sequences
- **Sequential Notes**: Press `z` to play all notes from C4 to G5 sequentially.
- **Replay Played Chords**: Press `w` to replay all notes played in the session.

### Project Structure

- **`main.py`**: The main script containing the Karplus-Strong algorithm implementation and logic for real-time note playing and visualization.
- **`README.md`**: Project documentation (this file).

###  Acknowledgments

- The Karplus-Strong algorithm was developed by Kevin Karplus and Alex Strong in 1983 for digital sound synthesis.
- This project was inspired by the desire to simulate guitar string sounds using physical modeling techniques in Python.lgorithm

