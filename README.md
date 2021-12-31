# NJUPT Big Team Project for Software Engineering
Jupyter-powered Customer Classification Software.
## _Team list:_
### F18030115 Alladin Al-Gannam
### F19030132 Anna Akulova

## Features

- Simple and easy to use professional software for business
- Beautiful visualizations based on your csv data
- Import, save and even export results as PDF
- Web-based application
- Using bleeding-edge technologies in AI

## Tech

Our project uses a number of open source projects to work properly:

- [Python](https://www.python.org/) - easy and fast programing language
- [Jupyter-notebook](https://jupyter.org/) - awesome web-based environment
- [Tensorflow](https://www.tensorflow.org/) - end-to-end open source platform for machine learning


## Installation

The project requires:
- numpy==1.20.1
- pandas
- tensorflow
- keras
- sklearn
- pycaret
- seaborn
- matploitlib
- scikit-optimize

Clone this repository:

```sh
git clone https://github.com/hetake2/njupt-teamproject-2021
cd njupt-teamproject-2021/
```

Run pip to install libs:

```sh
pip install -r requirements.txt
```

Start the app by script:

```sh
sh start.sh
```


## How-to-use

In order to use this app, simply edit Data_Insurance_TGI.csv file and run the program to see results.
For users we recommend to run all sections before "4. Transform & Compare Models in PyCaret".

## For Devs

Thanks to the Jupyter framework, we are able to store and edit code directly in our program, 
so, you can feel free to edit it and instantly get the results.

Starting from "4. Transform & Compare Models in PyCaret" section, you can train your own model for this project,
but you have to use an Nvidia GPU and Cuda drivers.


## License

GNU GPL 3

**Free Software, Hell Yeah!**
