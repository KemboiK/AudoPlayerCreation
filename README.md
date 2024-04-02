# AudoPlayerCreation
## Java Audio Player
This Java program allows you to play, stop, reset, and quit audio playback using the Java Sound API. It utilizes the javax.sound.sampled package to handle audio input and output.

## Prerequisites
Java Development Kit (JDK) installed on your system
Compatible audio file in WAV format (example: "Whats Up.wav")
# Getting Started
1.Clone or download the repository to your local machine.
2.Make sure you have a compatible audio file in WAV format that you want to play. Rename the file if necessary and place it in the same directory as the Java source code.
3.Compile the Java source code using the command:
javac Main.java
4.Run the compiled program using the command:
java Main
# Usage
Once the program is running, you can interact with it using the following commands:

P (Play): Start playing the audio file.
S (Stop): Pause the audio playback.
R (Reset): Reset the playback position to the beginning of the audio file.
Q (Quit): Quit the program and close the audio clip.
Enter the corresponding letter for each command and press Enter to execute the action.

## Example
P=play,S=Stop,R=Reset,Q=Quit
Enter your choice: P
# Notes
Only WAV audio files are supported by this program.
Make sure the audio file is accessible and correctly named in the source code.
