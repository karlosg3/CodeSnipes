# CodeSnipes
## Objective
A real-time, collaborative code editing platform focusing on high-concurrency synchronization using CRDTs.
## Core Tech Stack

  - Frontend: React + Vite

  - Editor: Monaco Editor (VS Code Engine)

  - Synchronization: Yjs (CRDT Framework)

  - Communication: WebSockets (Socket.io)

  - Backend: Node.js + Express

  - Deployment: Dockerized environment

## Architecture Overview
The application follows a Peer-to-Server-to-Peer model. The server manages "Rooms" via Socket.io, while Yjs handles conflict resolution on the client side to ensure all participants reach eventual consistency.
