# McScrims Staff Client

Internal staff control client for the McScrims Minecraft Network. This is a secure desktop application built with Electron, React, and TypeScript for monitoring and managing the Minecraft network infrastructure.

## Commands

- **STRG + K** - Open a global search menu

## Features

- Secure staff authentication
- Real-time server monitoring via WebSocket
- Server management (start, stop, restart, kill)
- Live metrics display (TPS, MSPT, CPU, Memory)
- Admin role-based access control
- Desktop notifications for events

## Security

- Context isolation enabled
- Node integration disabled
- Secure preload script with minimal API surface
- JWT token stored in memory only
- Role-based access control

## Requirements

- Node.js 18+
- Windows 10/11 (primary target)
- Staff account credentials
