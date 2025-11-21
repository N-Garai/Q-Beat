# Q-Beat 🎵⚛️

**Quantum Music Generation using Qiskit**

Transform quantum mechanics into musical compositions! Q-Beat uses quantum computing principles to generate unique, professional-quality music with multiple instruments, scales, and song structures.

## ✨ Features

### 🎹 Advanced Music Generation
- **Multi-instrument composition**: Independent drum, bass, and melody tracks
- **Multiple musical scales**: Major, minor, pentatonic, blues, and more
- **Chord progressions**: Pop, jazz, blues, and epic progressions
- **Bass patterns**: Root, walking bass, synth bass, and harmonic patterns
- **Professional song structure**: Intro, verses, chorus, bridge, and outro with dynamic transitions

### ⚛️ Quantum-Powered
- **Quantum circuits** for rhythmic and melodic patterns
- **Superposition & entanglement** for creating complex musical variations
- **Quantum probability** mapped to audio amplitude
- **Phase information** used for harmonic richness

### 🎼 Technical Capabilities
- 44.1kHz 16-bit WAV audio export
- Variable BPM (60-180)
- MIDI note system with frequency conversion
- ADSR envelope shaping for realistic instruments
- Multi-track mixing with independent volume control
- Reverb and audio effects

## 📁 Project Structure

```
Q-Beat/
├── Q-Advance_Song_Generator.ipynb    # Advanced multi-instrument composer
├── Q-Beat_Music_Generation_Demo.ipynb # Basic quantum music demo
├── Advance-song/                      # Generated song files
│   ├── quantum_jazz.wav
│   ├── quantum_blues.wav
│   ├── quantum_epic.wav
│   ├── quantum_modal.wav
│   └── quantum_song_60s.wav
└── demo_music file/                   # Demo music samples
    ├── quantum_drum_sequence.wav
    └── quantum_polyrhythm.wav
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install qiskit qiskit-aer numpy scipy matplotlib pylatexenc ipython
```

### Quick Start

1. Clone the repository:
```bash
git clone https://github.com/N-Garai/Q-Beat.git
cd Q-Beat
```

2. Open the notebooks in Jupyter:
```bash
jupyter notebook
```

3. Run `Q-Beat_Music_Generation_Demo.ipynb` to generate your first quantum song!

## 🎵 Usage Examples

### Generate a Song

```python
from quantum_music import QuantumSongComposer, AdvancedAudioSynthesizer

# Initialize synthesizer
synth = AdvancedAudioSynthesizer(sample_rate=44100)

# Create composer
composer = QuantumSongComposer(
    synth, 
    bpm=120, 
    scale='A_minor', 
    progression='jazz'
)

# Compose and save
song = composer.compose_complete_song(total_duration=60)
synth.save_wav(song, 'my_quantum_song.wav')
```

### Available Configurations

**Scales:**
- C_major, A_minor, G_major, E_minor, D_major, B_minor
- F_major, Cm_pentatonic, Blues

**Progressions:**
- `pop`: I-vi-IV-I
- `blues`: I-I-IV-I
- `jazz`: I-ii-IV-V
- `epic`: I-IV-V-I

**Bass Patterns:**
- `root`: Simple root notes
- `root_fifth`: Root + fifth harmonic
- `walking`: Complex walking bass
- `synth`: Modern synth bass

## 🎼 How It Works

1. **Quantum Circuit Creation**: Builds quantum circuits with superposition, entanglement, and rotation gates
2. **Quantum Measurement**: Executes circuits and extracts probability distributions and phase information
3. **Audio Synthesis**: Maps quantum data to musical parameters (pitch, amplitude, phase)
4. **Multi-track Composition**: Generates separate drum, bass, and melody tracks
5. **Song Structure**: Arranges sections (intro, verse, chorus, bridge, outro) with dynamic variations
6. **Audio Export**: Mixes tracks and exports to high-quality WAV files

## 📊 Generated Music Examples

The `Advance-song/` folder contains examples of different musical styles:
- **quantum_jazz.wav** - A minor, jazz progression, 100 BPM
- **quantum_blues.wav** - E minor, blues progression, 90 BPM
- **quantum_epic.wav** - G major, epic progression, 140 BPM
- **quantum_modal.wav** - C minor pentatonic, pop progression, 110 BPM

## 🔬 Technical Details

- **Quantum Framework**: IBM Qiskit
- **Audio Processing**: NumPy, SciPy
- **Visualization**: Matplotlib
- **Music Theory**: MIDI note system, standard chord progressions
- **Synthesis**: Additive synthesis with ADSR envelopes

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new musical scales or progressions
- Implement new quantum circuit patterns
- Enhance audio effects and synthesis methods
- Improve song structure algorithms

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Nayananshu Garai**
- GitHub: [@N-Garai](https://github.com/N-Garai)

## 🙏 Acknowledgments

- IBM Qiskit team for the quantum computing framework
- Music theory principles from classical composition
- Quantum computing community for inspiration

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Made with ⚛️ quantum mechanics and 🎵 music theory**
