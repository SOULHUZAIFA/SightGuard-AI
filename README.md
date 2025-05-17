# SightGuard AI

**Real-Time Smart Surveillance with AI-Powered Insights**

![SightGuard Dashboard](./assets/screenshot.png)

## 🔍 Overview

SightGuard AI is an open-source, full-stack surveillance platform that transforms live camera feeds into actionable intelligence. It leverages cutting-edge AI models to detect objects, classify activities, and generate natural language incident reports, enhancing security monitoring for various environments.

## 🚨 Features

- **Live Object Detection**: Identifies humans, vehicles, and other key objects in real-time.
- **Activity Classification**: Recognizes behaviors such as loitering, running, or fighting.
- **Natural Language Reports**: Generates concise summaries of detected incidents.
- **Voice Narration**: Converts text reports into speech for auditory alerts.
- **Interactive Dashboard**: Visualizes incidents with timelines and geolocation mapping.
- **Scalable Architecture**: Designed for easy deployment and future expansion.

## 🧠 AI Tasks Utilized

- `object-detection`
- `video-classification`
- `text-generation`
- `text-to-speech`

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript
- **Backend**: Go (API server), Python (AI inference)
- **AI/ML**: Hugging Face Transformers, OpenCV, FFmpeg
- **Database**: PostgreSQL
- **Messaging**: Redis
- **Deployment**: Docker, Kubernetes (optional)

## 📦 Getting Started

### Prerequisites

- Node.js
- Go
- Python 3.8+
- PostgreSQL
- Redis
- Docker

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sightguard-ai.git
   cd sightguard-ai
