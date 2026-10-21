# WebMargaritas: Application Architecture

## Overview

WebMargaritas is a web-based marketplace for digital advertising services. The application allows visitors to browse service categories, explore individual service pages, and interact with the ordering interface.

The project combines a browser-based frontend with a Node.js backend and a Linux-based production environment.

## High-Level Architecture

```text
User's Browser
      |
      | HTTP / HTTPS
      v
Nginx Web Server
      |
      | Reverse Proxy
      v
Node.js + Express.js
      |
      v
Application Routes and Static Assets
```

This diagram represents the main application request flow. Additional integrations and data storage components are not shown here.

## Technology Stack

| Component | Technology | Purpose |
|---|---|---|
| Frontend | HTML, CSS, JavaScript | User interface and client-side interactions |
| Backend | Node.js, Express.js | Server-side application and HTTP routing |
| Web server | Nginx | Handles incoming web traffic and reverse proxying |
| Process management | PM2 | Runs and manages the Node.js application process |
| Operating system | Linux | Production server environment |
| Version control | Git, GitHub | Source code management and change history |

## Main Application Areas

- **Service catalog:** helps users browse advertising services by category and platform.
- **Service pages:** provide details about individual services.
- **Shopping cart:** supports the ordering workflow.
- **Case studies and reviews:** present project examples and social proof.
- **Backend routing:** handles HTTP requests through the Express application.

## My Role

I independently developed and maintained the website, implemented frontend and backend functionality, deployed the application, and fixed issues discovered during testing and operation.

## Scope

This document describes the high-level architecture. It intentionally excludes private source code, credentials, server addresses, and other sensitive deployment details.
