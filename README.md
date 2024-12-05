# Python Bindings Sample Code Repo

1. suggestion is to install python virtual envirionment and then start and activate it:

```console
$ sudo apt install python3-venv
$ python3 -m venv venv
$ source venv/bin/activate
```

2. In the irtual environment - 'venv', to be able to run the code, you must first install the requirements:

```console
$ pip install -r requirements.txt
```

3. Then you can run 'invoke' commands to build and / or test those binding operations, a few examples as below:

```console
$ invoke --list
$ invoke all
$ invoke build-cmult
$ invoke test-ctypes
```