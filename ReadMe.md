# One-Way Transmission using WebRTC

![WebRTC Logo](https://webrtc.org/assets/images/webrtc-logo-horiz.svg)

This repository provides a simple implementation of one-way data transmission using WebRTC. It allows you to establish a WebRTC data channel for sending text data from one user to another in a real-time and peer-to-peer manner.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

WebRTC (Web Real-Time Communication) is a powerful technology that enables real-time communication directly between web browsers or other platforms. This project demonstrates how to use WebRTC to establish a data channel for one-way text data transmission.

### Key Features

- Establish a WebRTC connection between peers.
- Create a data channel for sending text messages.
- Real-time transmission of text data from the sender to the receiver.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/praTeek271/One-way-tranmission.git
   ```

2. Navigate to the project directory:

   ```bash
   cd One-way-tranmission
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your web browser and access the application at [http://localhost:3000](http://localhost:3000).

## Usage

1. Open the application in two separate browser tabs or on two different devices.
2. In one tab or device, click the "Create Offer" button. This will generate an offer to establish a WebRTC connection.
3. In the other tab or device, click the "Accept Offer" button to establish the connection.
4. Once the connection is established, you can enter text messages in the "Message" input field and click the "Send" button to transmit the message to the other peer.
5. The received messages will be displayed in the chat area.

## Contributing

Contributions to this project are welcome! If you would like to contribute, please follow these guidelines:

1. Fork the repository and create your branch from `main`.
2. Make your changes and ensure the code passes any existing tests.
3. Create a pull request describing your changes and the issue it fixes or feature it adds.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to modify and expand upon this template to provide more detailed information about your project, its dependencies, or any specific usage instructions. Be sure to update the sections with the relevant information for your project.