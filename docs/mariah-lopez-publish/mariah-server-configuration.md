---
title: Mariah Lopez Development Server Configuration
author: Mariah Lopez
status: draft
audience: developers
tags: [technical, infrastructure]
---

# Server Configuration

This document explains the configuration settings used in the development server environment.

Use these settings to configure the development server environment.

## Server Settings

The development server uses the following configuration:

- **Host:** api.acme-internal.com
- **Port:** 8080
- **Timeout:** 60 seconds

## System Configuration

The server configuration includes the following settings:

- API version: v4.2.1
- Caching enabled
- Maximum users: 500

### Feature Flags

The system currently supports the following experimental features:

- beta_dashboard
- dark_mode

## Known Issues

The **Dark Mode** feature may crash if it is clicked twice.  
If this occurs, refresh the page to resolve the issue.

## Running the Server

Follow these steps to start the server:

1. Open your terminal  
2. Run: `npm run start:prod`  
3. Make sure Node.js version 14 or higher is installed  

The server will start using the configuration settings listed above.
**Requirements:** Node.js version 14 or higher.

## Server Process Overview
The diagram below shows the steps to take when processing the server.  
```mermaid
flowchart TD
A[Start Server] --> B[Load Configuration]
B --> C[Connect to API]
C --> D[Run Application]
```
