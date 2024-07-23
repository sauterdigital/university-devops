- Creating the virtual environment: 
```bash
virtualenv venv
```

- Activatingv the virtual environment:
```bash
source venv/bin/activate
```
- Installing dependencies:
```bash
pip install -r requirements.txt
```

- Running the code:
```bash
python main.py
```


### Steps to run the python code withing a Docker container

- Build the image:
```bash
docker build -t university-devops:lastest
```

- Run the container:
```bash
docker run university-devops:latest 
```


