                                                   ##################################
                                                   #       Simple Number Reader     #
                                                   #		using *TF*          #
                                                   ##################################

			%This Code contains as ipynb File which is the source code for a Number Reader using Tensorflow and Keras.%


- The Dataset used is MNIST Dataset which contains 28*28 sized Pictures of handwritten digits.

- Building a Sequential model which contains 2 RNN layes and 2 Dense Layers.

- Using LSTM from tf.keras.layers (Which is the cpu version, although you can use CuDNNLSTM if you have configured the tf_gpu, Link for that at the end).

- My Saved model is NumReader.h5 which can be easily loaded using load_model from tf.keras.model

