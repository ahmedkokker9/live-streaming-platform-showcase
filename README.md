# Professional Live Streaming System for Educational Platform

## Overview

This project showcases the implementation of a complete live streaming and virtual classroom solution integrated into an existing educational platform.

The goal was to extend the platform with a production-ready live classroom system that enables teachers to conduct online lessons with real-time communication, lecture recording, and cloud storage while maintaining excellent performance and scalability.

**Live Platform:**
https://bakr-taher.com/

> **Note:** The source code is not included because this project was developed for a private client under a confidentiality agreement.

---

## Project Highlights

- Professional virtual classroom integration
- Live streaming using WebRTC & LiveKit
- Teacher & Student dedicated interfaces
- Secure session management
- Teacher camera & microphone support
- Screen sharing
- Live chat
- Automatic lecture recording
- Cloud storage integration (Cloudflare R2)
- Scalable server architecture
- Optimized backend performance
- Responsive UI for desktop and mobile

---

## Technologies Used

### Frontend
- React
- TypeScript

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### Live Streaming
- LiveKit
- WebRTC

### Storage
- Cloudflare R2

### Infrastructure
- Docker
- Hetzner VPS

---

## Architecture

The system consists of three main components:

- Frontend application
- Backend API
- Dedicated LiveKit media server

Recorded lectures are automatically uploaded to Cloudflare R2, allowing scalable cloud storage without increasing server disk usage.

---

## Main Features

- Create live classroom sessions
- Join sessions securely
- Teacher video streaming
- Student participation
- Real-time communication
- Screen sharing
- Live chat
- Automatic recording
- Cloud upload
- Responsive design
- Production-ready architecture

---

## Performance Optimizations

Several optimizations were implemented to ensure stable performance under concurrent sessions:

- Reduced server resource consumption
- Optimized media streaming
- Efficient recording pipeline
- Scalable infrastructure
- Clean and maintainable architecture

---

## Project Gallery

Screenshots of the platform are available inside the **screenshots/** folder.

---

## Live Demo

https://bakr-taher.com/

---

## Disclaimer

This repository is intended to showcase the project implementation only.

The original source code belongs to the client and cannot be shared publicly due to confidentiality agreements.
