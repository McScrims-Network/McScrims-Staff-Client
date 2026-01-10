# McScrims Staff Client

Internal staff control client for the McScrims Minecraft Network. This is a secure desktop application built with Electron, React, and TypeScript for monitoring and managing the Minecraft network infrastructure.

## Commands

- **Ctrl + K** - Open global search menu (Command Palette)

## Features

- **Secure Authentication** - Staff login with role-based access control
- **Real-time Monitoring** - Live tracking of TPS, MSPT, CPU, and RAM usage via WebSocket
- **Server Management** - Start, stop, restart, and kill server instances
- **File Manager** - Integrated file browser with **Monaco Editor** for direct config editing
- **Live Console** - Interactive terminal (XTerm.js) for viewing logs and sending commands
- **Global Search** - Quick navigation to servers and tools
- **System Tray** - Background monitoring and quick status access
- **Desktop Notifications** - Alerts for critical server events

## Upcoming Features (Roadmap)

We are constantly working to improve the McScrims Staff Client. Here is what's coming next:

- **Advanced Log Explorer** - Browse and search through historical server logs and compressed archives.
- **Plugin Management** - View, toggle, and install plugins directly from the dashboard.
- **Network-wide Player Manager** - See all online players across the network with quick actions (Kick, Ban, Teleport).
- **Bulk Commands** - Execute console commands on multiple server instances simultaneously.
- **Backup Integration** - Create and restore server backups using the Pterodactyl API.
- **Enhanced Metrics** - Detailed historical graphs for performance monitoring over longer periods.

## Tech Stack

- **Electron** - Desktop application framework
- **React** - UI framework
- **TypeScript** - Type-safe development
- **Vite** - Fast build tooling
- **Zustand** - State management
- **Tailwind CSS** - Styling
- **Axios** - HTTP client
- **WebSocket** - Real-time communication
- **Monaco Editor** - Code editor integration
- **XTerm.js** - Terminal emulation

## Security

- Context isolation enabled
- Node integration disabled
- Secure preload script with minimal API surface
- JWT token stored in memory only
- Role-based access control

## Requirements

- Windows 10/11 (primary target)
- Staff account credentials
