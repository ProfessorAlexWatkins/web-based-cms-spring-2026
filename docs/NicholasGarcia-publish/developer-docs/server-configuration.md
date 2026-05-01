---
title: Server Configuration
author: Nicholas Garcia
status: draft
---
## Server Configuration

This page contains the server settings for the Acme Corp development environment. Use these settings to connect to the server and get started.

### Server Settings

- Host: api.acme-internal.com
- Port: 8080
- Timeout: 60s

### Getting Started

To start the server, run the following command in your terminal:

```bash
npm run start:prod
```

You must have Node v14 or higher installed. If you need to update Node, visit the [Node.js website](https://nodejs.org).

```mermaid
flowchart TD
    A[Start]--> B{Is Node v14 or higher installed?}
    B -- Yes --> C[npm run start:prod]
    B -- No --> D[Update Node]
    C --> E[Connect to api.acme-internal.com on port 8080]
    E --> G{Enable Dark Mode?}
    G -- Yes --> H{Did it crash?}
    H -- Yes --> I[Refresh the page]
    H -- No --> F[Done]
    G -- No --> F[Done]
  ```
  