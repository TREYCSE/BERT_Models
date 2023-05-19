# Welcome to Virtual Detention | Backend
### Model Functionality + User Data = Developer Data

#### ToolKit Summary [Full Stack Application]:
1. Full Stack Application: TensorFlow REST Framework
2. TensorFlow BERT models for Natural Language Question Answering: Answer questions based off content of a given passage, serving as a virtual tutor once ML algorithms with BERT complete deployed as RESTful API, can then integrate with React/Node.js frontend! [Typescript TensorFlow models converted to js [using tensorflow converter] and deployed as JSON RESTful API to render output to the frontend
using Tensorflow & javascript backend, with React.js & Node.js frontend.]
3. Docker - Containerize: https://docs.docker.com/get-started/02_our_app/
4. Heroku - Deploying: https://dashboard.heroku.com/apps

### SERVER: Tensorflow.js Backend CPU
#### Usage - This package implements a JavaScript based CPU backend to TensorFlow.js.
###### https://github.com/tensorflow/tfjs/tree/80a809108ca3c3976acaf5e03af709eb39472a5c/tfjs-backend-cpu
#### Importing the backend
###### Note: this backend is included by default in @tensorflow/tfjs.

    Via NPM
    // Import @tensorflow/tfjs-core
    import * as tf from '@tensorflow/tfjs-core';
    // Adds the CPU backend to the global backend registry.
    import '@tensorflow/tfjs-backend-cpu';

    
### CRUD: Storing BERT output/answers as new JSON file
######  frontend output save to to backend json file (get backend?) how use TS CPU + JS SERVER - SERVER RIGHT?, NEED TF RESTful API for CRUD? not inc with BERT API?
###### later user authentication will allow account creating and saving answers to profile 

