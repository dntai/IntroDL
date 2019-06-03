# Deep Learning Example Programs
Nguyen Hai Duong

Huynh Van Thong (update)

Professor Kim Soo Hyung  
Chonnam National University  
    
## Environment
0. Windows x64
1. Python 3.5 or later
2. TensorFlow
3. Keras
3. CUDA 8.0 or later (optional, GPU only)
4. cuDNN v5 or later (optional, GPU only)

## ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) Environment Setup 1 (with GPUs)
1. Download and install [Anaconda 2019.03 with Python 3.7](https://repo.anaconda.com/archive/Anaconda3-2019.03-Windows-x86_64.exe)
2. Open Anaconda Command Prompt
3. Install `TensorFlow-GPU` by entering `conda install -c anaconda tensorflow-gpu keras-gpu`

## ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Environment Setup 2 (with GPU Tesla K80 + Google Colab)
A **_free of charge_** way to experience training deep models with high-performance GPU!
1. Visit [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)
2. Sign in with you personal Google account
3. Menu `File` > `New Python 3 notebook`
4. Menu `Runtime` > `Change runtime type` > `Hardware acceleration` > `GPU` > `Save`  
(Note that python source codes will be saved in your Google Drive, and a work shift lasts for 12 hours)  
5. Let's get started with [this Jupyter Notebook](https://github.com/th2l-aipn/IntroDL/blob/master/examples/colab_getting_started.ipynb) (how to use GPU, execute Linux commands, install Python packages, and read data from Google Drive)

## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Environment Setup 3 (with CPUs)
1. Download and install [Anaconda 2019.03 with Python 3.7](https://repo.anaconda.com/archive/Anaconda3-2019.03-Windows-x86_64.exe)
2. Open Anaconda Command Prompt
3. Install `TensorFlow` by entering `conda install -c conda-forge tensorflow`
4. Enter `conda install -c conda-forge keras` to install Keras

## Usage
1. Download `.ipynb` files to your computer. For example, `D:\dl`
2. Open Command Prompt, type `cd /d D:\dl`
3. Enter `jupyter notebook`
4. `Jupyter IDE` will be opened in a web browser, open one of the downloaded programs
5. Select menu `Cell` > `Run All` to run the program

## Credit

[https://github.com/nhduong/intro_deep](https://github.com/nhduong/intro_deep)
