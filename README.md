# Auto Test Framework

Automated test suite generation from API specs and user stories.

## Features
- Auto-generate tests from OpenAPI specs
- Business logic edge case detection
- REST, GraphQL, WebSocket support
- CI/CD integration
- Visual diff reporting

## Installation
```
pip install -r requirements.txt
```

## Usage
```
python main.py generate openapi.yaml --output tests/
python main.py run tests/ --report html
```

## License
MIT