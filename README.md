# Speech Command Classification

### ([Flask](https://github.com/pallets/flask) + SpeechCommandClassification+ [Recorderjs](https://github.com/mattdiamond/Recorderjs))

1) Flask is a micro web framework written in Python.
2) SpeechCommandClassification Your own speech command classification model, with support for converting speech command to text.
3) Recorderjs A plugin for recording/exporting the output of Web Audio API nodes 

### Project stucture
```
root
    |speech_command_classification.ipynb: Notebook for model experiments 
    |config: config for flask server and AI model
    |models: model architecture/checkpoints and inference code
    |static: js and css files for frontend
    |templates: html files for frontend
    |app.py: Flask app
    |Dockerfile
    |requirements.txt
```
### Detail about the experiments


### Build docker and run

```
docker build -t speech_command .
docker run --rm -p4999:5000 -v$PWD:/code speech_command
```


![Homepage](https://github.com/gnvml/Speech-Command-Classification-with-Flask/blob/master/upload/home.png)
![Demo](https://github.com/gnvml/Speech-Command-Classification-with-Flask/blob/master/upload/demo.png)
