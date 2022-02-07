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

# Inspiration 🎵
All four of us are musicians, we've run into the problem countless times where we want to have the sheet music for some song, but the software for it is expensive or requires a high level of technical knowledge. We wanted to create a program that simplifies this process while maintaining a low overhead to keep this program accessible to all.

# What it does 😀
Score.me, is a web-based application that accepts audio files and converts them into sheet music. It is basically a friend with perfect pitch telling you what each note is and when to play them! With a fully working user authentication feature, the app also retains a catalogue for your personal account. You can access your previously uploaded songs, as long as you have an internet connection!

# How we built it 🧑‍💻
We created our backend in Python utilizing Flask, our database in MongoDB with Google Cloud, and our front-end in ReactJS. Although we had the option to take the ML route, we decided that in the interest of accessibility and maintaining low overhead, we utilize an algorithm called Fast Fourier Transform to determine the hz of a given sound and then approximate those values to notes, allowing the program to run much faster and compute light results while maintaining a high level of accuracy.

# Challenges we ran into 🧗🏻 ⏱
We ran into trouble getting accurate approximations for notes and creating a back-end that could process these files and output them as scores. It can also be difficult to normalize audio files that have irregularities or unexpected notes in them, along with the library limitations we found.

# Accomplishments that we're proud of 🙌 👏
We are extremely proud of the final product we were able to create, the flow of user creation to uploading your first song is seamless and the accuracy that the algorithm provides is very strong, and we only have more ideas to improve it.

# What we learned 📚
We learned a lot about the integration of the front-end with backend and product design, we initially found that these two items, specifically in regards to file management can be difficult to handle, but we learned how to effectively balance them. We also learned a lot about how many extra variables you have to deal with when not working with sanitized data, and writing code that works around those restrictions.

# What's next for Score.me 🎼
Improving our accuracy in regards to musical rests is our top priority, as well as moving to a production format that allows us to host our project.

Built With
