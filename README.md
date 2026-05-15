# Achac Server Documentation

## 📖 Table of Contents
1. [Introduction](#introduction)
2. [Quick Start](#quick-start)
3. [Configuration Guide](#configuration-guide)
4. [Defense Wall Configuration](#defense-wall-configuration)
5. [API Reference](#api-reference)
6. [Performance Tuning](#performance-tuning)
7. [Troubleshooting](#troubleshooting)
8. [Best Practices](#best-practices)

## Introduction

### Overview
Achac Server is a high-performance, event-driven web server built with asynchronous non-blocking architecture. It can easily support tens of thousands to hundreds of thousands of concurrent connections on standard hardware.

### Key Features

#### 🚀 High Performance
- Event-driven model with zero thread context switching
- Asynchronous non-blocking I/O
- Zero-copy file transmission
- Efficient memory management (< 2KB per connection)

#### 🛡️ Enterprise Security
- DOS/CC attack defense
- IP rate limiting (configurable thresholds)
- Connection flood protection
- SQL injection prevention
- XSS attack filtering
- Path traversal protection

#### 🔄 Load Balancing
- Multiple algorithms (Round Robin, Least Connections, IP Hash)
- Automatic health checking
- Backend failover support
- Weight-based distribution

#### 📁 Static File Serving
- High-performance file delivery
- Directory listing with styling
- MIME type auto-detection
- File caching mechanism
- Range request support

## Quick Start

### System Requirements
- **Java**: JDK 11 or higher
- **OS**: Windows / Linux / macOS
- **Memory**: 256MB minimum (512MB+ recommended)
- **Disk**: 50MB for server + static files

### Installation

#### 1. Download/Clone
```bash
git clone [https://github.com/achac/achac-server.git](https://github.com/358207017/Achac-Server2/new/main?filename=README.md)
cd achac-server
