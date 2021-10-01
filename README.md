# HackTheNorth2021
We wanted to create a program that simplifies this process while maintaining a low overhead to keep this program accessible to all. This was our (Alexander Yoshino, Justin Zheng, Simon Li, Allen Lu) project for HackTheNorth2021.

We created our backend in Python, utilizing Flask, our database in MongoDB, and our front-end in ReactJS. Although we had the option to take the ML route, we decided that in the interest of accessibility and maintaining low overhead, we utilize an algorithm called fast fourier transform to determine the frequency of a given sound and then approximate those values to notes, leading to much faster results while maintaining a high level of accuracy.

We hope that Score.me will lower the bar for entry into music and make it more accessible to all.
We offer low compute time, our storage method allows for easy conversion to multiple types of outputs, we can create pdfs on demand, and we have a responsive front-end design that makes it easy for anyone to access our application.

# Setup
1) Create virtual environ:

For Windows users:
virtualenv venv     # create your virtual environment
./venv/Scripts/activate # activate your newly created virtual environment

For Mac users:
virtualenv venv -p python3.8
source venv/bin/activate

2) pip install -r requirements.txt
