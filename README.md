# Template for Data Engineering

## Homework Setup
1. Create venv (serves as kafka consumer)
```python
python3 -m venv venv
```

2. Activate venv
```python
source venv/bin/activate
```

3. Install requirements
```python
pip install -r requirements.txt
```

4. Start Kafka server (Producer)
```bash
docker-compose up -d
```

## [Homework](./homework.md)