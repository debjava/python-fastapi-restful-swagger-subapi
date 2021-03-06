![DDLAB](./images/A22.png)
# RESTful microservice API development using Python FastAPI with subapi for Swagger docs

# Technicalities
RESTful API development with Python FastAPI with subapi for Swagger docs.

This is an example project which performs the followings

* **HTTP GET Functionality**
* **HTTP POST Functionality**
* **HTTP PUT Functionality**
* **HTTP PATCH Functionality**
* **HTTP DELETE Functionality**
* **HTTP File Download Functionality (Multipart)**
* **Streaming file download**
* **Show the image**
* **HTTP File Upload Functionality (Multipart)**
* **HTTP Multiple File Upload Functionality (Multipart)**

you can access thr swagger docs [Swagger Docs](http://localhost:8090/myapp/docs#)

Here I am using FastAPI specific annotation with respect to OpenAPI docs for generating Swagger documentation


## Python Version

`py -V` or `python -V`

current python version: **3.7.4**

## How to create a virtual environment

syntax is `py -m venv` <enviornment name>

In this case, the example is given below.

* Step 1: Execute the command using `py -m venv env`

* Step 2: Activate using the command `.\env\Scripts\activate`

* Step 3: Verify using the command `where python`

## Install dependencies in Virtual environment

If you have requirments.tx file, you have to apply the following command to install all dependencies.

`pip install -r requirements.txt`

To see the list of installed dependencies, use the below command

`pip freeze`

### Ensure proper version of PIP
In the virtual environment use the following command,

`pip list`

After executing, you may get the following details.

>(env) E:\pydev-1-2020\projectDependencyInstall>pip list
Package    Version
---------- -------
pip        19.0.3
setuptools 40.8.0
You are using pip version 19.0.3, however version 20.0.2 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.
>

### Upgrade PIP version
Execute the following command to upgrade to higher version of pip.

`py -m pip install --upgrade pip`

or

`python -m pip install --upgrade pip`

### Final step to install dependencies

After activating the virtual environment, execute the following command

`pip install -e .`

or

`pip install .`

### How to run

In Eclipse or Pycharm, run the file `main.py`

In the browser navaigate to [Swagger Docs](http://localhost:8090/myapp/docs#)

Conclusion
==========
Learn, explore more and share with all.

![DDLAB](./images/dd-logo.png)
