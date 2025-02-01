# About Dataset

The dataset consists of four files containing motor foot EEG data, specifically designed for analyzing both real and imagined movements. The files include:

- **Right Real Motor Foot Signal (MRF)**: Contains the actual electrical activity recorded from the right foot during motor tasks.
- **Left Real Motor Foot Signal (LRF)**: Similar to the right foot, this file captures the electrical activity from the left foot during real movements.
- **Right Imagined Foot Signal (IRF)**: Captures the imagined movement EEG signals for the right foot.
- **Left Imagined Foot Signal (ILF)**: Captures the imagined movement EEG signals for the left foot.

All signals were filtered within a frequency range of **8 Hz to 30 Hz** to eliminate noise and focus on relevant motor activity. Additionally, Mel-frequency cepstral coefficients (MFCCs) were applied as a feature extraction method, allowing for a more effective representation of the signals for further analysis, such as classification or pattern recognition tasks.

The data is saved as **NumPy arrays (.npy)**.
