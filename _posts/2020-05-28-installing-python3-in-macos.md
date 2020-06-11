---
title: Installing Python3 in macOS
date: 2020-05-28T00:00:00.000Z
last_modified_at: 2020-06-11T11:20:20.969Z
tags:
  - "#Python3"
  - "#Installation"
---
Starting from macOS Catalina, Python2 & Python3 is installed by default in macOS.You can check by entering `python3 --version` command in Terminal.

![This image shows python3 version](/assets/images/uploads/2020-05-28-0.png)

Now Enter `python2 --version`  or `python --version` to check if python2 was installed. Remember entering just `python` defaults to python2.

![This image shows python2 version](/assets/images/uploads/2020-05-28-1.png)

## [](https://pip.pypa.io/en/stable/)Pip

[Pip](https://pip.pypa.io/en/stable/) also called as Pypi is a package manager for python. For installing new packages and to update existing packages for our projects, we need pip.

### Download pip

But there's no pip installed by default. We have to install pip by downloading and running python file get-pip.py.

* Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py) file.
* Go to the directory where get-pip.py file exists and execute file by entering `python3 get-pip.py`
* You can check installation by entering `pip --version`

> Note: Open new terminal window to check pip installation so that environment variables take in effect.

Yay! You've now configured how to start with python.