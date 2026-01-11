# CodeChat (p2p-comms)

CodeChat is a high-performance, serverless peer-to-peer (P2P) communication platform. By leveraging WebRTC via the PeerJS library, it facilitates direct data exchange between browser nodes, eliminating the need for intermediary servers or centralized databases to handle message traffic.

## Core Functionality

| Module | Technical Implementation |
| :--- | :--- |
| **P2P Networking** | Utilizes WebRTC data channels for low-latency, direct browser-to-browser links. |
| **Authentication** | Client-side "Identity Vault" utilizing localStorage for persistent session management. |
| **Admin Panel** | Elevated privilege system for network broadcasting and local session clearing. |
| **User Interface** | Modern glassmorphism aesthetic built with vanilla CSS and Inter typography. |

## System Architecture

CodeChat operates on a decentralized model. Unlike traditional chat apps that upload data to a cloud server, CodeChat uses a signaling server only to facilitate the initial "handshake." Once the connection is established, the signaling server is bypassed, and data flows directly between users.



## Setup and Deployment

### Technical Requirements
* A modern web browser with WebRTC support (Chrome, Firefox, Safari, Edge).
* Standard HTTPS hosting (required for PeerJS functionality in most browsers).

### Local Installation
1.  Clone the repository to your local machine:
    ```bash
    git clone [https://github.com/bingkahu/p2p-comms.git](https://github.com/bingkahu/p2p-comms.git)
    ```
2.  Navigate to the directory and open `index.html`.
3.  No external package managers (npm/yarn) or backend environments (Node.js/Python) are required for core operation.

## Project Roadmap

* **SubtleCrypto Integration:** Implementing end-to-end encryption (E2EE) for all transmitted strings.
* **Binary Data Transfer:** Enabling P2P file sharing via ArrayBuffer streams.
* **Mesh Networking:** Transitioning from 1-on-1 sessions to multi-peer mesh groups.
* **Node Logging:** Exporting session transcripts to local JSON files.

## Contact and Support

For technical inquiries, collaboration proposals, or general feedback, please reach out via the following channel:

* **Lead Maintainer:** mgrassi1@outlook.com

## Legal and Licensing

### Disclaimer of Liability
This software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

### Privacy Notice
CodeChat does not collect, store, or sell user data. All communication is transient and occurs directly between users. However, users are responsible for the security of their own Peer IDs. Sharing a Peer ID publicly may allow unauthorized nodes to attempt a connection.

### Licensing
This project is open-source. Please refer to the LICENSE file in the repository for full terms regarding redistribution and modification.
