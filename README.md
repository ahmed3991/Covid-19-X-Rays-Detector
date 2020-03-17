# Covid-19 X-rays Detector

[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()


> A web app to detect covid-19 with accuracy of 92%-90% from chest X-rays of patients 


## Getting started in 10 minutes

- Clone this repo 
- Install requirements
- Run the script
- Go to http://localhost:5000
- Done! :tada:

:point_down: Screenshot:

<p align="center">
  <img src="/static/screenshot.png" height="480px" alt="">
</p>

------------------

## Run with Docker

With **[Docker](https://www.docker.com)**, you can quickly build and run the entire application in minutes :whale:

```shell
# 1. First, clone the repo
$ git clone https://github.com/ahmed3991/Covid-19-X-Rays-Detector
$ cd Covid-19-X-Rays-Detector

# 2. Build Docker image
$ docker build -t covid19_app .

# 3. Run!
$ docker run -it --rm -p 5000:5000 covid19_app
```

Open http://localhost:5000 and wait till the webpage is loaded.

## Local Installation

It's easy to install and run it on your computer.

```shell
# 1. First, clone the repo
$ git clone https://github.com/ahmed3991/Covid-19-X-Rays-Detector
$ cd Covid-19-X-Rays-Detector

# 2. Install Python packages
$ pip install -r requirements.txt

# 3. Run!
$ python app.py
```

Open http://localhost:5000 and have fun. :smiley:

<p align="center">
  <img src="/static/screenshot.gif" height="480px" alt="">
</p>

------------------

## Future

1) Enrich the dataset with another real cases.
2) Improve the detection accuracy.
3) Hosting the app.[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=965CZ8WNR4Q7C)


## More resources

[Pretty & simple image classifier app template](https://github.com/mtobeiyf/keras-flask-deploy-webapp)

[Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)

[Open database of COVID-19 cases with chest X-ray or CT images](https://github.com/ieee8023/covid-chestxray-dataset)


