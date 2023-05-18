# Welcome to Virtual Detention - Backend

#### ToolKit Summary [Full Stack Application]:
1. Full Stack Application: TensorFlow REST Framework
2. TensorFlow BERT models for Natural Language Question Answering: Answer questions based off content of a given passage, serving as a virtual tutor once ML algorithms with BERT complete deployed as RESTful API, can then integrate with React/Node.js frontend! [Typescript TensorFlow models converted to js [using tensorflow converter] and deployed as JSON RESTful API to render output to the frontend
using Tensorflow & javascript backend, with React.js & Node.js frontend.]

## ENVIRONMENT
##### ML Hardware: (optional - for metadata)
##### Coral: USB accelerator set up guide: https://coral.ai/docs/accelerator/get-started/ & https://coral.ai/docs/accelerator/datasheet/

### Deploying TensorFlow Models as RESTful API 
##### Docker - Containerize: https://docs.docker.com/get-started/02_our_app/
##### https://www.mlq.ai/django-machine-learning/

### API Documentation
#### Tensorflow.js Client-Side RESTful API: https://www.tensorflow.org/tfx/serving/api_rest#encoding_binary_values
#####  Making Requests/Request format: The request body for the classify and regress APIs must be a JSON object formatted as follows:

    {
      // Optional: serving signature to use.
      // If unspecifed default serving signature is used.
      "signature_name": <string>,

      // Optional: Common context shared by all examples.
      // Features that appear here MUST NOT appear in examples (below).
      "context": {
        "<feature_name3>": <value>|<list>
        "<feature_name4>": <value>|<list>
      },

      // List of Example objects
      "examples": [
        {
          // Example 1
          "<feature_name1>": <value>|<list>,
          "<feature_name2>": <value>|<list>,
          ...
        },
        {
          // Example 2
          "<feature_name1>": <value>|<list>,
          "<feature_name2>": <value>|<list>,
          ...
        }
        ...
      ]
    }
<value> is a JSON number (whole or decimal), JSON string, or a JSON object that represents binary data (see the Encoding binary values section below for details). <list> is a list of such values. This format is similar to gRPC's ClassificationRequest and RegressionRequest protos. Both versions accept list of Example objects.

### CRUD: Storing BERT output as new JSON file
###### later user authentication will allow account creating and saving answers to profile

### TENSORFLOW MACHINE LEARNING MODELS + METADATA
##### Tensorflow Models
##### Natural Language Question Answering: https://towardsdatascience.com/implementing-question-answering-networks-with-cnns-5ae5f08e312b
##### BERT: https://arxiv.org/abs/1810.04805 , GH: https://github.com/google-research/bert
##### Example: https://github.com/tensorflow/examples/tree/master/lite/examples/bert_qa/ios
##### Pre-trained TensorFlow.js models: https://github.com/tensorflow/tfjs-models




