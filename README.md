# messaging-protocols

This repository serves as a centralized hub organizing multiple standalone repositories that each implement and demonstrate different lightweight, efficient, and fast real-time messaging and notification protocols.

These were implemented by the developer for practicing, comparing, and understanding a variety of real-time communication techniques across different protocol layers and tech stacks.

---

## Included Protocol Implementations

### Completed

| Repository | Protocol                  | Protocol Layer     | Main Working Technique                | Tech Stack                    |
| ---------- | ------------------------- | ------------------ | ------------------------------------- | ----------------------------- |
| `sse`      | Server-Sent Events        | Application (HTTP) | Unidirectional event streaming        | Spring boot, React            |
| `mqtt-web` | MQTT underneath WebSocket | Transport (WS)     | MQTT messaging tunneled underneath WS | Mosquitto, Spring boot, React |

### Under Development

| Repository | Protocol      | Protocol Layer  | Main Working Technique        | Tech Stack                    |
| ---------- | ------------- | --------------- | ----------------------------- | ----------------------------- |
| `N/A`      | MQTT over TCP | Transport (TCP) | Lightweight publish/subscribe | Mosquitto, Spring boot, React |

### In Queue

| Repository | Protocol            | Protocol Layer | Main Working Technique             | Tech Stack                      |
| ---------- | ------------------- | -------------- | ---------------------------------- | ------------------------------- |
| `N/A`      | WebRTC Data Channel | P2P Transport  | Peer-to-peer low-latency streaming | WebRTC APIs, Spring boot, React |

---

This repository will continue growing as new protocol implementations are added, creating a comprehensive resource for real-time messaging protocol experimentation and education.
