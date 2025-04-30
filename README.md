# Payment ISO Standards API

A simple Flask API to explore payment ISO messaging standards (8583, 20022, and 7813).

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the API

Start the Flask development server:
```bash
python app.py
```

The API will be available at `http://localhost:5000`

## Endpoints

### GET /api/iso-standards
Returns a list of available ISO standards for payment messaging.

Example response:
```json
{
    "standards": [
        {
            "name": "ISO 8583",
            "description": "Financial transaction card originated messages",
            "year": 1987
        },
        {
            "name": "ISO 20022",
            "description": "Universal financial industry message scheme",
            "year": 2004
        },
        {
            "name": "ISO 7813",
            "description": "Identification cards - Financial transaction cards",
            "year": 2006
        }
    ]
}
``` 