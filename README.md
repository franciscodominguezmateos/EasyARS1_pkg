# EasyARS1_pkg
A ROS package that include a single word Automatic Recognition Speech and Speaker Identification in 20 lines of pyton code EasyASR1.py, this can be used without ROS.

Installation
Install dependenties
 
Scipy
sudo apt-get install python-scipy

SKlearn
sudo apt-get install python-sklearn

SOX sound package in order to record from mic
sudo apt-get install sox

python_speech_features
https://github.com/jameslyons/python_speech_features

http://python-speech-features.readthedocs.io/en/latest/

http://www.practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/
This project is on pypi

To install from pypi:

sudo pip install python_speech_features

From this repository:

git clone https://github.com/jameslyons/python_speech_features
sudo python setup.py develop

Install fastdtw
https://github.com/slaypni/fastdtw

sudo pip install fastdtw

And finally put in cd to your catkin_ws/src folder and do a
git clone https://github.com/franciscodominguezmateos/EasyARS1_pkg

rosrun EasyARS1_pkg recognizer.py

There is a little voice command from pocketsphinx ros node I recommend you to customize it.

rosrun EasyARS1_pkg voice_comd_vel.py

