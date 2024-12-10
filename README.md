```markdown
# Voice Recorder

A simple Python-based voice recording application using `sounddevice` and `soundfile` libraries. This project provides a GUI to start and stop the voice recording process. The recorded audio is saved as a `.flac` file.

## Features

- Record audio using the `sounddevice` library.
- Save recorded audio in `.flac` format using `soundfile`.
- Simple GUI with Tkinter for ease of use.

## Requirements

This project requires Python 3.x and the following libraries:

- `sounddevice` - for audio recording functionality.
- `soundfile` - for saving audio data to a file.
- `tkinter` - for the graphical user interface (GUI).

You can install the required dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/marpot/voice_recorder.git
    ```

2. Navigate to the project folder:
    ```bash
    cd voice_recorder
    ```

3. Create and activate a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the `voice_recorder.py` script:
    ```bash
    python voice_recorder.py
    ```

2. The GUI will open with a button labeled "Start Recording".
3. Press the "Start Recording" button to begin recording. The recording will last for 5 seconds and be saved as `my_audio_file.flac` in the current directory.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The `sounddevice` library for audio recording.
- The `soundfile` library for saving recorded audio.
- The `tkinter` library for building the simple GUI.
```

Replace the placeholder `https://github.com/your-username/voice_recorder.git` with your actual GitHub repository URL.

This `README.md` provides an overview of your project, installation instructions, usage guide, and credits to the libraries you're using.