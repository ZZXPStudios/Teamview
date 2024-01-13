# Video Calling Software

This is a Python 3 based video calling software designed to work on Android and Termux. It allows users to establish a peer-to-peer video call using the VNC protocol.

## Prerequisites

Before running the code, make sure you have the following libraries and dependencies installed:

- socket
- cv2
- threading
- pygame
- pygame.camera
- subprocess
- os
- sys
- tigervnc
- nginx

## Usage

1. Install the required libraries and dependencies.
2. Run the code using Python 3.
3. Follow the on-screen instructions to start or stop a video call.

## Functions

- `video(conn)`: Sends and receives video frames during a call.
- `audio(conn)`: Sends and receives audio streams during a call.
- `start_call(conn)`: Starts a video call.
- `stop_call(conn)`: Stops an ongoing video call.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
