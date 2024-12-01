# WebRTC Chat

This project provides a WebRTC-based chat service that allows a "Host" and a "Peer" to communicate with each other in a secure and private manner. The code for this project is made available strictly for use in the provided service, and users are not allowed to use, modify, or redistribute the code outside of the intended service.

## Features

- **Host**: The host creates an offer and waits for the peer to send an answer.
- **Peer**: The peer receives the host's offer, generates an answer, and communicates with the host.
- **Text Chat**: Send messages back and forth once the connection is established.
- **Data Channels**: Used for peer-to-peer communication.

## Usage

To use this service, follow these steps:

### Step 1: Start the Host

1. Open the `host.html` file in your browser.
2. Click on **Generate Offer** to create an offer.
3. Copy the generated offer and send it to the Peer (via email, message, etc.).

### Step 2: Start the Peer

1. Open the `peer.html` file in your browser.
2. Paste the Host's offer into the **Offer** textarea.
3. Click **Generate Answer** to create an answer.
4. Send the answer back to the Host.

### Step 3: Wait for Messages

Once the connection is established, you can start messaging the other party. The messages will appear in the chat box.

## License

This project is licensed under a custom license. You are permitted to use this software only through the provided service. You are not allowed to use, copy, or modify the underlying code. See the [LICENSE](LICENSE) file for full terms and conditions.

### VPN Recommendation

If you wish to hide your IP address and protect your privacy when using this service, the author recommends using a VPN or other privacy-enhancing technologies.

## Privacy & Security

While this service uses WebRTC for peer-to-peer communication, the host and peer should exercise caution when using the service in untrusted environments. Always use a VPN if you wish to protect your IP address and ensure that the host/peer cannot track your location or identity.

## No Warranty

This software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, or non-infringement. In no event shall the author be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

## Contact

For any questions or feedback, feel free to reach out to the author.

