# SmartAIX Trading Server
Python server for MT5 SmartAIX trading indicator.

## Setup
1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Run locally:
```bash
python smart_aix_server.py
```

## API Endpoints
- POST /predict - Get trading signals
- GET /health - Server health check

## Configuration
Set the following environment variables:
- PORT (default: 5000)
- MODEL_PATH (optional)
