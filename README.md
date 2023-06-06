## Razorops CI/CD pipeline demo with Python  

If you have forked this repo, then connect with Razorops to create your demo pipeline by following the below button

[![Connect](https://github.com/razorops-public/images/blob/main/connect_with_github.svg)](https://dashboard.razorops.com/get-github-installation-link-for-org)

This is an example code to demonstrate how to create [Python](https://www.python.org/doc/) based pipeline on [Razorops](https://docs.razorops.com/).

It's a simple API written in [Flask framework](https://flask.palletsprojects.com/en/1.1.x/) in Python and includes a test suite. 

### Local Setup

1. Use `pip` to install the dependencies -

        pip install -r requirements.txt


2. To start the server in development mode run - 

        python app.py

### Execute tests

Run following commands to execute the test suite - 

        python test.py

### CI/CD pipeline

If you're new to Razorops, feel free to fork this repository and use it to [create a project](https://docs.razorops.com/getting_started/).

`.razorops.yaml` contains the pipeline code to build and execute the tests for this project. To know more about how to write and customize, refer to the [documentation](https://docs.razorops.com). Here is the link of [the pipeline](https://dashboard.razorops.com/apps/bold-grass-9882/workflows) workflows page.

### Recommended links

* This example uses the Ubuntu based [Linux-VM](https://docs.razorops.com/buildenv/overview) build envirement, which has a subset of python versions available. If you want to customize version, you can use [Docker](https://docs.razorops.com/buildenv/overview) based build envioronment. For more details, please refer to ["Choose Python version"](https://docs.razorops.com/guides/python/#specify-python-version)
* How to integrate [Junit reports](https://docs.razorops.com/pipeline/reports/) with Razorops.
* How to [cache dependencies](https://docs.razorops.com/pipeline/caching/) to speed-up the workflow.

### License

Copyright (c) 2021 Razorops LLC

Distributed under the MIT License. See the file LICENSE.md.
