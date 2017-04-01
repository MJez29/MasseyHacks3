## Machine Learning with Python

Python is a fairly easy language to pick up and is oftentimes a good first language.

In case you don't have Python, you can download version 3.6.1 from [here](https://www.python.org/downloads/).

### Dependencies

#### Windows

You may need to run your command line as an administrator. 

##### Numpy

Open [http://www.lfd.uci.edu/%7Egohlke/pythonlibs/#numpy](http://www.lfd.uci.edu/%7Egohlke/pythonlibs/#numpy) in a web browser and click the link that matches your system. You want the "cp##" portion of the link to match your python version, and the number at the end needs to be chosen based on whether you're running 32-bit or 64-bit. 

For example, if you have python 3.6 and have 64-bit windows, you need to click: `numpy‑1.12.1+mkl‑cp36‑cp36m‑win_amd64.whl`

`python -m pip install {path-to-file}`

##### Scipy

Open [http://www.lfd.uci.edu/%7Egohlke/pythonlibs/#scipy](http://www.lfd.uci.edu/%7Egohlke/pythonlibs/#scipy) in a web browser and click the link that matches your system. You want the "cp##" portion of the link to match your python version, and the number at the end needs to be chosen based on whether you're running 32-bit or 64-bit. 

For example, if you have python 3.6 and have 64-bit windows, you need to click: `scipy‑0.19.0‑cp36‑cp36m‑win_amd64.whl`

`python -m pip install {path-to-file}`

##### SciKit-Learn

`python -m pip install scikit-learn`

#### MacOS

Open terminal and run:

`sudo pip install numpy`

`sudo pip install scipy`

`sudo pip install scikit-learn`

---

#### Test Dependencies

Run a python shell in the command line or open IDLE and run:

`import sklearn`

If it doesn't throw an error, you're good to go.
