# Intro about gTalk Bot


## Installation Steps: (for windows)  

### FAQ: 
```bash
python version == 3.7.7 (64 bit)
```

### To install Rasa and Rasa X 
```python
virtualenv venv37 -p C:\Program Files\Python37\python.exe
virtualenv env -p C:\Users\User\AppData\Local\Programs\Python\Python36\python.exe
```
activate the python environment

```bash
pip install -r requirements.txt
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple


```


## when the default port (5002) is busy?  

----------------------------------------------------------------------------------
### (Only Rasa) How i can run it another port, when the default port (5002) is busy?  
```bash
rasa run -m models --enable-api --cors “*” --debug -p 5004
```

### (Rasa X) Run it on different server 
```bash
rasa x --debug --enable-api --cors "*" --port 5003 --rasa-x-port 5004
```
----------------------------------------------------------------------------------
