# Intrinsic Motivation Recognition of Students in Classroom Situations

This project contains experimental code for training end-to-end neural models to automatically recognize the motivational levels from students, using only their facial expressions as input.

Contact person: Pedro Santos, santos@ukp.informatik.tu-darmstadt.de

https://www.ukp.tu-darmstadt.de/

https://www.tu-darmstadt.de/


Don't hesitate to send us an e-mail or report an issue, if something is broken (and it shouldn't be) or if you have further questions.

## Project structure
* `python_scripts` -- this folder contains scripts used to run the experiments described in the paper. The CNN implementation is an extension of the discriminator implemented here: https://github.com/carpedm20/DCGAN-tensorflow

## Requirements

* Python 3
* Tensorflow
* Numpy
* Scipy
* Keras
* Scikit-learn
* PyYaml
* OpenCV
* FFMpeg
* OpenFace

## Installation

* FFMPeg

https://www.ffmpeg.org/download.html

* OpenCV

https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_setup/py_table_of_contents_setup/py_table_of_contents_setup.html#py-table-of-content-setup

* OpenFace

https://github.com/TadasBaltrusaitis/OpenFace

* Python dependencies

```
$ virtualenv --system-site-packages -p python3 motivation_recognition_venv
$ source motivation_recognition_venv/bin/activate
(motivation_recognition_venv) $ pip install --upgrade pip
(motivation_recognition_venv) $ pip install --upgrade -r requirements.txt
```
