# Welcome to Virtual Detention
### Backend | Model Functionality + User Data = Developer Data

#### ToolKit Summary [Full Stack Application]:
1. Full Stack Application: TensorFlow REST Framework
2. TensorFlow BERT models for Natural Language Question Answering: Answer questions based off content of a given passage, serving as a virtual tutor once ML algorithms with BERT complete deployed as RESTful API, can then integrate with React/Node.js frontend! [Typescript TensorFlow models converted to js [using tensorflow converter] and deployed as JSON RESTful API to render output to the frontend
using Tensorflow & javascript backend, with React.js & Node.js frontend.]
3. Docker - Containerize: https://docs.docker.com/get-started/02_our_app/
4. Heroku - Deploying: https://dashboard.heroku.com/apps

### SERVER; Tensorflow.js Backend CPU
#### Usage - This package implements a JavaScript based CPU backend to TensorFlow.js.
###### https://github.com/tensorflow/tfjs/tree/80a809108ca3c3976acaf5e03af709eb39472a5c/tfjs-backend-cpu
#### Importing the backend
###### Note: this backend is included by default in @tensorflow/tfjs.

    Via NPM
    // Import @tensorflow/tfjs-core
    import * as tf from '@tensorflow/tfjs-core';
    // Adds the CPU backend to the global backend registry.
    import '@tensorflow/tfjs-backend-cpu';

    
### CRUD: Storing BERT output as new JSON file
###### later user authentication will allow account creating and saving answers to profile
### API Documentation


### TensorFlow BERT Machine Learning Resources
    1. Tensorflow Models
    2. Natural Language Question Answering: https://towardsdatascience.com/implementing-question-answering-networks-with-cnns-5ae5f08e312b
    3. BERT: https://arxiv.org/abs/1810.04805 , GH: https://github.com/google-research/bert
    4. Example: https://github.com/tensorflow/examples/tree/master/lite/examples/bert_qa/ios
    5. Pre-trained TensorFlow.js models: https://github.com/tensorflow/tfjs-models

