# Waveshare-3S-Monitor

A Python script to monitor a Waveshare UPS Module 3S

## Setup

```bash
# Download the script and license files
curl -fsSLO https://raw.githubusercontent.com/Guiorgy/Waveshare-3S-Monitor/refs/heads/main/ina219.py
curl -fsSLO https://raw.githubusercontent.com/Guiorgy/Waveshare-3S-Monitor/refs/heads/main/LICENSE
chmod +x ina219.py

# Setup a virtual environment
python3 -m venv venv
venv/bin/pip install smbus2
```
