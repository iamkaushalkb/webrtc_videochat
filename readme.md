# WebRTC Video Chat

![WebRTC](https://img.shields.io/badge/WebRTC-Technology-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

WebRTC Video Chat is an open-source project that provides a simple and customizable solution for real-time video chat applications using WebRTC technology. With this project, you can easily create video chat applications, add them to your website, or use them as a starting point for more complex applications.

## Features

- Real-time video and audio communication
- Support for text chat alongside video
- Customizable UI to fit your project's branding
- Screen sharing
- Peer-to-peer and server-based signaling options
- Cross-browser compatibility

## Getting Started

### Prerequisites

Before you begin, make sure you have the following prerequisites:

- Node.js and npm installed
- Web server for hosting the application (e.g., Apache, Nginx)
- Basic knowledge of JavaScript and HTML

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/webrtc-video-chat.git
cd webrtc-video-chat
```
2. Install dependencies:
```bash
npm install
```

3. Configure your server settings in config.js and Build the project:
```bash
npm run build
```

### Usage

1. Clone the repository:
```bash
<script src="path/to/webrtc-video-chat.js"></script>
<link rel="stylesheet" type="text/css" href="path/to/webrtc-video-chat.css">
```
2.Create a container for the video chat:
```bash
<div id="video-chat-container"></div>
```
3. Initialize the video chat:
```bash
const videoChat = new WebRTCVideoChat({
  container: 'video-chat-container',
  // Customize options if needed
});
```
4. Customize the UI, add event listeners, and integrate with your application as required.

### Contributing
Contributions to this project are welcome. If you have any ideas, feature requests, or find a bug, please open an issue or create a pull request
