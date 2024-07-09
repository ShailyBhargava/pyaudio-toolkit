**#PyAudio Recorder**
This project captures audio input from the microphone and saves it as a WAV file using the PyAudio and wave modules. The script initializes an audio stream, records the audio until interrupted, and then writes the recorded data to a WAV file.

**Requirements**:

Python 3.x,
PyAudio,
wave.

**Installation**

**Clone the repository:**
"git clone https://github.com/your-username/pyaudio-recorder.git",

"cd pyaudio-recorder"

**Install the required packages:**
pip install pyaudio

**Run the script to start recording:**
python main.py(file name),

To stop recording, interrupt the process (e.g., press Ctrl+C).

The recorded audio will be saved as myrecording.wav in the current directory.

**Code Overview**
The main script performs the following steps:

**Initialization:**

Imports the pyaudio and wave modules.
Creates a PyAudio object.

**Audio Stream Setup:**

Opens an audio stream with a sample format of 16-bit PCM, mono channel, and a sampling rate of 44.1 kHz.
Sets the buffer size to 1024 frames.
**Audio Recording:**

Continuously reads audio data from the stream and appends it to a list (frames) until interrupted by the user (e.g., pressing Ctrl+C).
**Stream Termination:**

Stops and closes the audio stream.
Terminates the PyAudio object.

**Saving the Recording:**
Opens a new WAV file named "myrecording.wav".
Sets the number of channels, sample width, and frame rate for the WAV file.
Writes the recorded audio frames to the file.
Closes the WAV file.


Feel free to modify the sections to better fit your project needs.





Saving the Recording:

Opens a new WAV file named "myrecording.wav".
Sets the number of channels, sample width, and frame rate for the WAV file.
Writes the recorded audio frames to the file.
Closes the WAV file.
