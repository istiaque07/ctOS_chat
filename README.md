# ctOS_chat
an ipchat based p2p chat app [https://istiaque07.github.io/ctOS_chat/]
ctOS - Decentralized IP Chat & Mesh Network

A fully decentralized, peer-to-peer (P2P) WebRTC data channel and Bluetooth LE communication gateway built for secure, serverless messaging.

🌟 Introduction

ctOS is an advanced decentralized multi-peer and Bluetooth mesh chat application. Unlike traditional messaging platforms that rely on central servers or cloud databases, ctOS operates entirely via browser-to-browser WebRTC DataChannels and Web Bluetooth LE technologies. There are no middlemen, no cloud databases, and no central points of failure.

🚀 Key Features

True Decentralization:

No central server stores your data. Your chat messages and file transfers travel directly across peer-to-peer tunnels.

Multi-Peer WebRTC Mesh:

Establish and maintain direct encrypted data channel connections with multiple peers simultaneously, enabling group chat broadcasting across the mesh network.

Web Bluetooth LE Radio Bridge:

Communicate and bridge data with nearby Bluetooth LE peripheral devices even without an active internet connection.

QR Code Pairing & Generation:

Instantly generate your operator QR code or use your camera to scan peer QR codes for rapid, frictionless node connection.

Secure P2P File Sharing:

Transfer images, documents, and files directly through encrypted channels (supporting payloads up to 2MB or browser memory limits).

Real-Time Console Diagnostics:

Monitor live packet counters, connection states, and debugging logs through an integrated developer terminal stream.

🏗️ Architecture & Security

Signaling (Sign-up & Matchmaking): PeerJS cloud signaling servers are used exclusively for initial handshaking and IP/ICE candidate exchange. Once the handshake is complete, the signaling server is entirely bypassed, and traffic flows directly between peers.

Encryption (End-to-End): Built upon WebRTC's native DTLS/SRTP protocols, ensuring robust end-to-end encryption (E2EE) for every message and file packet.

Zero Storage: There is no backend database. Chat histories reside solely in your browser's temporary memory or local buffers, leaving zero digital footprints on remote servers.

💻 Tech Stack

HTML5 / CSS3 / JavaScript (Vanilla)

Tailwind CSS (Modern dark mode UI styling)

PeerJS (WebRTC) (P2P Data Channel networking)

Web Bluetooth API (Proximity radio bridge communication)

QRCode.js & Html5-qrcode (QR generation and live camera scanning)

Lucide Icons (UI iconography)

🚀 How to Run

Open the index.html file in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox).

Enter your Operator Codename or alias, and click Initialize Mesh Node.

Share your unique Peer Address with another user or generate/scan your QR code to pair instantly.

Once connected, begin secure messaging or file transfer across the decentralized mesh!

Developed with decentralized resilience for secure communications.
