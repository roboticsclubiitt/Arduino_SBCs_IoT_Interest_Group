# Pianostairs

Pianostairs is a fun and interactive project designed to transform a mundane staircase into a musical instrument. Installed at the entrance of our college fest, Pianostairs offers an engaging experience where each step triggers a corresponding note of the piano Sargam. 

## How It Works

Pianostairs utilizes an ultrasonic sensor to detect steps taken by individuals. When someone steps on the stairs, the ultrasonic sensor detects the presence of the person and sends a signal to an Arduino Mega board. The Arduino Mega processes this signal and triggers the playback of a specific piano note associated with the step.

To enhance the responsiveness and ensure multiple responses can be handled simultaneously, hyperthreading is employed in a laptop connected to the Arduino Mega. This allows for seamless interaction and ensures that each step is accurately detected and produces the intended musical note.

The piano sound is generated directly from the laptop and is played through a speaker, creating an immersive auditory experience for participants.

## Installation

To set up Pianostairs for your own event or installation, follow these steps:

1. **Hardware Setup**: 
   - Connect the ultrasonic sensor to the Arduino Mega board according to the specifications provided in the schematic diagram.
   - Ensure the speaker is connected to the audio output of the laptop.

2. **Software Installation**:
   - Download and install Arduino IDE for programming the Arduino Mega.
   - Download and install Processing IDE for programming the laptop to handle multiple responses.

3. **Programming**:
   - Upload the Arduino code provided in the `Arduino_Code` directory onto the Arduino Mega.
   - Run the Processing sketch provided in the `Processing_Sketch` directory on the laptop.

4. **Testing**:
   - Once the setup is complete, test the functionality by stepping on the stairs and verifying that each step triggers the corresponding piano note.

## Contributors

- [Prakhar](https://www.github.com/prax-1/)
- [Bhavesh]()
- [Divyam](https://www.GitHub.com/divyam27-1/)
- [Rohit]()

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank our college for providing the opportunity to showcase our project at Tirutsava.
