🛰️ CodeChat Sentinel v5.1
Enterprise-Grade Peer-to-Peer Communication Protocol
CodeChat Sentinel is a sophisticated, browser-based messaging framework designed for secure, direct communication. By leveraging a decentralized mesh architecture, it eliminates the need for intermediary servers, ensuring that data transmission remains strictly between authorized nodes.

🛡️ Protocol Security & Legal
Data Sovereignty
CodeChat operates on a Zero-Persistence model. No message data, metadata, or session logs are stored on external servers. All communication exists solely within the temporary memory (RAM) of the active browser session and is purged upon termination.

Privacy Disclosure
Direct Peer-to-Peer (P2P) connections facilitate the exchange of data packets directly between users. While this provides significant privacy advantages, it necessitates the visibility of public IP addresses between connected nodes. Users requiring complete IP anonymity are advised to operate within a Virtual Private Network (VPN).

Terms of Operation
This software is provided "as is." The developers assume no liability for the misuse of this protocol or for any content transmitted through the mesh. Users must adhere to local regulations and organizational policies.

📋 System Changelog
v5.1 (Sentinel)
Node Verification: Integrated a validation engine to confirm node existence before attempting a handshake.

Session HUD: Implemented a "Current Chat" header for real-time tracking of the active peer link.

Error Handling: Added localized audio alerts and visual indicators for failed connection attempts.

v4.9 - v5.0
Fleet Management: Restored active node tracking within the management interface.

Handshake Optimization: Resolved synchronization issues to allow for seamless multi-node entry.

UX Refinement: Transitioned to standard authentication terminology and hardened the logout lifecycle.

🛠️ Implementation & Use
Authentication: Initialize your session by providing a unique handle and your authorized password at the entry gate.

Node Identification: Your unique 6-digit Node ID is generated upon entry and is visible in the primary navigation sidebar.

Establishing a Link: To initiate a secure tunnel, enter the target Node ID into the Remote Link field.

Session Termination: To securely wipe your session data and disconnect from the mesh, use the Log Out command located at the base of the sidebar.

⚙️ Technical Specifications
Framework: PeerJS (WebRTC Implementation)

Signal Processing: Web Audio API (Synthesized Feedback)

Interface: Optimized CSS3 Grid / Flexbox

Typography: Plus Jakarta Sans & JetBrains Mono
