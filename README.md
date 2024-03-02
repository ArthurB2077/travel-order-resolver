# Travel Order Resolver
This is a simple travel order resolver. It is a simple console application that reads a file with travel orders and resolves them. The application is written in Python 3.11

## How to run
To run the application, you need to have Python 3.11 installed. Then you can run the application by running the following command in the console:
```bash
python3 -m pip install poetry
poetry install
source .venv/bin/activate
poe run
```

You must then first:
- Select `Training` from the options list
- Generate both datasets
- Train both models

After that, you can resolve travel orders by selecting `Whisper` (with audio) or `Interactive` (with text) from the first options list.
# travel-order-resolver
