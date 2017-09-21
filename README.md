# installTensorFlowJetsonTX
Install TensorFlow on the NVIDIA Jetson TX1 or TX2 from the provided wheel files

Python .whl files for installing TensorFlow. 

# Installation
There are two directories in this repository, TX1 and TX2. First, install the matching pip for your Python installation. Then install the wheel file from the directory that matches your Jetson model, and version of Python:

### Python 2.7
$ sudo apt-get install python-pip

$ pip install <em>tensorflow wheel file</em>

### Python 3.5
$ sudo apt-get install python3-pip

$ pip3 install <em>tensorflow wheel file</em>


# Build Information
There are wheel files for Python 2.7 and Python 3.5
The Jetson environment:
* L4T 28.1 (JetPack 3.1)
* CUDA 8.0
* cuDNN 6.0

TensorFlow
* Version 1.3.0 
* Built with CUDA support

Full directions used for building the wheel files:

* NVIDIA Jetson TX1: https://github.com/jetsonhacks/installTensorFlowTX1
* NVIDIA Jetson TX2: https://github.com/jetsonhacks/installTensorFlowTX2

<em><b>Note:</b> The Jetson TX1 uses a GPU architecture to 5.3, the Jetson TX2 is 6.2. The builds reflect this.</em> 
