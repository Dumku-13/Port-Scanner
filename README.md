# Python Port Scanner 🔍

A multithreaded TCP port scanner built in Python with basic banner grabbing.

## Features
- Scan custom IP/domain and port ranges
- Multithreaded scanning for speed
- Banner grabbing (detect running services)
- Clean and sorted output
- Execution time tracking

## How it works
- Attempts TCP connections to target ports
- Identifies open ports
- Retrieves service banners (if available)

## Usage

```bash
python scanner.py
