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
 Also, in the code, I hard-coded the Github token and removed with a placeholder before commiting to Github. 

Flask run


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
<Mamud>:
In the code many optimations are possible.
1. Will check with python library (version) gives desired functionality and performance. As of no I used PyGithub==2.6.1
2. Will use logger for all logging purpose
3. Extend the exception handling section.
4. Code is working with GitHub repository. I need one more day to integrate the BitBucket repository.
5. I used only 1 GET method. Additional GET method with various parameters are very much possible.
6. Appropriate coding standard (Optum specific) has to be followed.


