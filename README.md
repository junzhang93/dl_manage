# dl_manage
A web-based management system for a machine learning system.

## Usage:
### 1. For Windows

(1) Install Python.

(2) Install Django and numpy.

    pip install django
    pip install numpy

(3) Build MXNet.

Go to <a href="http://mxnet.readthedocs.io/en/latest/how_to/build.html#installing-pre-built-packages-on-windows">this page</a>. Follow the instructions in the "Installing pre-built packages on Windows" section.

(4) Install the Python Package of MXNet.

Open the README.txt file in the compressed file downloaded in step(3), and follow corresponding instructions.

(5) Run this project.

Open CMD, and change the current directory to the project directory. Type the following command:

    python manage.py runserver 0.0.0.0:8000
    
Then, open a browser. Type `localhost:8000/manage` and press Enter.

### 2. For Ubuntu

(1) Install Python (if not installed).

(2) Install Django and numpy.

    sudo pip install django
    sudo pip install numpy

(3) Build MXNet.
Go to <a href="http://mxnet.readthedocs.io/en/latest/how_to/build.html#building-on-ubuntu-debian">this page</a>. Follow the instructions in the "Building on Ubuntu/Debian" section.

(4) Install the Python Package of MXNet.
Go to <a href="http://mxnet.readthedocs.io/en/latest/how_to/build.html#python-package-installation">this page</a>. Follow the instructions in the "Python Package Installation" section.

(5) Run this project.

Open Terminal, and change the current directory to the project directory. Type the following command:

    python manage.py runserver 0.0.0.0:8000
    
Then, open a browser. Type `localhost:8000/manage` and press Enter.
