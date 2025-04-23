# Coding Challenge App

A skeleton flask app to use for a coding challenge.

## Install:

Configured virtual environment (venv) using below commands:
```
python3 -m venv .venv
source .venv/bin/activate

```
Did "pip install" from the requirements file

``` 
pip install -r requirements.txt

```
## Code Build

```
# Skeleton code is developed using VSCode.
 The Github token is maintained in config file and is read by python code. However, the the token is removed from config file at the time of comitting the code to github. 

Also, Insomnia client is used for testing with REST API call. 
```

### Spin up the service

```
# start up local server

Flask run

```

### Making Requests

``` 
http://127.0.0.1:5000/org/mailchimp

```

## What'd I'd like to improve on...

In the code many optimations are possible.
1. Will check with python library (version) gives desired functionality and performance. As of no I used PyGithub==2.6.1
2. Will use logger for all logging purpose
3. Extend the exception handling section to address various scenarios.
4. Code is working with GitHub repository.
5. Code is yet tobe developed to integrate BitBucket repository. However the approach remains the same.
6. I used only 1 GET method. Additional GET method with various parameters are very much possible.
7. Appropriate coding standard (Optum specific) has to be followed.


