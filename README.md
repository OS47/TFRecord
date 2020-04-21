# TFRecord
This is a practice using and creating TFRecord data format which applied on skin cancer Dataset from udacity DL nano degree</br>
The idea of using TFRecord format is to take advantage from GPU utilization with TFData API instead of keras generator method</br>
Have a look to this website http://digital-thinking.de/tensorflow-vs-keras-or-how-to-speed-up-your-training-for-image-data-sets-by-factor-10/  which shows the performance differences</br>

There are Two files</br>
1- TFRecord-datasets.ipynb : which convert all data elements which are image pixels, label, height, width and channels</br>
2- TFRecord-datasets-without_dim.ipynb : convert only image path and label</br>

* The total size of dataset 5.2 GB</br>
* The total size of created TFRecord 120 GB ( no need to dataset any more )</br>

References :
- https://www.tensorflow.org/tutorials/load_data/tfrecord
- https://towardsdatascience.com/working-with-tfrecords-and-tf-train-example-36d111b3ff4d
