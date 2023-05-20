# Welcome to Virtual Detention | Phase 2 | SavedModel Converter and TensorFlow Serving + REST API |
#### What's being changed?
##### Used Tensorflowcpu pure js backend in my React app which doesn't add much functionality for things like data storage.
##### With TensorFlow Serving, a widely used package, I would have more power on the backend server and will operate CRUD to store the predictions from the model and be able to fine tune it as well as possibly integrate more as it is a high-level service.
##### This also means instead of importing the BERT model, I will be using the TensorFlow SavedModel method which uses the @tensorflow-converter to convert the saved model to Tensorflow.js.
###### Note: Depending on which type of model you’re trying to convert, you’ll need to pass different arguments to the converter. For example, let’s say you have saved a Keras model named model.h5 to your tmp/ directory. To convert your model using the TensorFlow.js converter, you can run the following command:

    $ tensorflowjs_converter --input_format=keras /tmp/model.h5 /tmp/tfjs_model
###### This will convert the model at /tmp/model.h5 and output a model.json file along with binary weight files to your tmp/tfjs_model/ directory. More details about the command line arguments corresponding to different model formats can be found at the TensorFlow.js converter README[https://github.com/tensorflow/tfjs/tree/master/tfjs-converter]. The BERT q&a models I selected were TypeScript files so after getting everything imported properly, I converted to json to get TensorFlow.js.
###### https://www.tensorflow.org/guide/saved_model
