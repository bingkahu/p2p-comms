# Security Policy

## Supported Versions

The following table identifies the versions of CodeChat (p2p-comms) that are currently receiving security updates.

| Version | Supported |
| ------- | --------- |
| 1.1.x   | :white_check_mark: |
| 1.0.x   | :x: |
| < 1.0   | :x: |

## Reporting a Vulnerability

If you discover a security vulnerability within this project, please do **not** open a public issue. Direct public disclosure makes the application less secure for everyone.

**How to report:**
1. **Draft a Report:** Include a detailed description of the vulnerability, steps to reproduce, and the potential impact.
2. **Submit:** Please send your report via GitHub Security Advisory or email the lead maintainer directly.
3. **Response Time:** You can expect an initial acknowledgement of your report within 48 hours.

## Security Architecture Notes

Since CodeChat is a Peer-to-Peer (P2P) application using PeerJS:
* **Data Privacy:** No messages are stored on a central server; they travel directly between nodes.
* **Local Storage:** Be aware that user credentials (if stored via the 'Identity' feature) are currently stored in the browser's localStorage in plaintext. Users should avoid using sensitive passwords on shared machines.
