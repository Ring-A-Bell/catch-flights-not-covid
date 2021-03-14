# catch-flights-not-covid

**catch-flights-not-covid** is an AI project that is aimed at helping the airport authorities enforce Covid social distancing rules and regulations. It helps in making people adhere to the new normal, by enforcing them to follow social distancing guidelines and wear masks. 


### Prerequisites
The project has been developed using 
Python, using PyCharm as IDE, and the modules used are  
`OpenCV2`\
`SQLite`\
`numpy`\
`imutils`\
`flask`\
`tensorflow`\
`Keras`\
`SQLite` is also required to run the database.

---

### Modules:
This project consists of three modules with a user interface; the modules are, namely, the social distancing module, mask detection module and face recognition module. The face detection module is the first, you would be expected to remove your mask, and show your face to the camera. The camera would then recognize your face and determine whether or not your flight is scheduled for that particular day. Then the mask detection module checks if the people are wearing masks, the social distancing module checks the distance between every pair of people and determines whether or not they are following the social distancing guidelines. 

---

### Setting up the project

#### Download and unzip to your preferred directory
##### To get the pictures for the dataset:
Run `faces_dataset.py`\
This will open your webcam and take about 50 pictures of you. (This entire project was developed and tested on PyCharm, we recommend you to test it on the same IDE)

##### Training the model to recognize your face:
Run `train_face.py`\
This will train the model with the pictures taken as the dataset.

##### Running the entire project/ viewing the website:
Now, we can run `main.py`\
Flask will render the web page and it opens on `127.0.0.1:5000` 

---

### Running the tests

You can click on the face detection button, and it will detect your face. 
Upon clicking the mask detection button, it will open your webcam and display the output, with a bounding box over your face, red if it’s no mask, and green if you are wearing a mask. 
With social distancing however, we have included a video, which will run and show whether the people are following distancing guidelines or not; red if they aren’t following and green if they are following the distancing guidelines.

### Built With

* [Python](https://www.python.org/) - Language
* [OpenCV](https://opencv.org/) - For computer vision
* [SQLite](https://www.sqlite.org/index.html) - Used to manage DB
* [Tensorflow](https://www.tensorflow.org/) - For image processing and prediction
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) - To render the webpage

---

### Authors

* [Sruti Verma](https://github.com/Srutiverma123)
* [Nithesh Gurudaas](https://github.com/nithesh-gurudaas)
* [Ram Gunasekaran](http://github.com/ramcalm)
* [Aditya Ganti](http://github.com/ring-a-bell)
