
# Read Me file

I am using **python 3.10.6**

# matching virtual environments

I have added a **requirements_v2.txt** files that can be used to install all the modules I have in my **venv** environment in a local venv environment.

I am using **tensorflow 2.10** because this is the reccomended version of tensorflow for windows machines that want to use a GPU

You can create a venv using the command

`py -m venv env`

You can activate it using 

`.\env\Scripts\activate`

You can install the modules from the requirements file in your venv by using the command 

`py -m pip install -r .\requirements.txt`

For anyone wanting GPU support for tensor flow please look at **TensorFlow_README.txt**
For anyone just wanting to use their cpu you won't need CUDA, but I do believe you will have to configure your install to default to targeting your CPU instead of searching for GPU. I don't think it has logic to do that on its own.