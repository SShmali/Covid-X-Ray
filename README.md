# Covid-19-X-ray-Classification
 Covid-19 classification model with 90% accuracy that uses Deep Learning to classify Covid-19 Patients from X-ray medical images.
 
## Dataset
The covid-19-chestxray dataset can be downloded from [This](https://github.com/ieee8023/covid-chestxray-dataset) Repo.

To prepare and build the dataset, run:
```
python build_covid_dataset.py --covid covid-chestxray-dataset --output dataset/covid
```
## Requirements
The main requirements are listed below:

* Tested with Tensorflow 2.7
* OpenCV 4.2.0
* Python 3.9
* Numpy
* Scikit-Learn
* Matplotlib
