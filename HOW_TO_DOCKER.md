# docker instructions

## build: ```flask % docker build -t rest-apis-flask-python .```

## run: ``` docker run -dp 5005:5000 -w /app -v "$(pwd):/app" rest-apis-flask-python sh -c "flask run --host 0.0.0.0" ```