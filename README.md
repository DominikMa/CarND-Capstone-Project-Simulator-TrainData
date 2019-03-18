# CarND-Capstone-Project-Simulator-TrainData
Some labeled data for the udacity CarND capstone project

The data was labeled with to [Vott](https://github.com/Microsoft/VoTT) tool. As labeles 'Green', 'Yellow' and 'Red' are used together with a [label map](./SimData-TFRecords-export/tf_label_map.pbtxt) taken from the [Bosch Small Traffic Lights Dataset](https://github.com/bosch-ros-pkg/bstld).


The labeled data can be found in the TFRecods format in [SimData-TFRecords-export](./SimData-TFRecords-export) or as plain json and JPG images in [vott-json-export](./vott-json-export). The file [SimData-export.json](./TFRecords/SimData-export.json) contains a list of regions for each image where each region has a tag ('Green', 'Yellow' or 'Red'), a bounding box and a list of corner points of the bounding box.
