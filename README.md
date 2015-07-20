# BreathDetection
Breath Detection in Python

## Dependencies
The code is tested to work under Python 2.7. It will probably work under Python 3+ too. 
It is tested to work under Ubuntu 14.04 and Windows 8.1 v6.3.9600 (both 64 bit).

The required dependencies are:
- Numpy >= 1.9
- Scipy >= 0.15
- librosa = 0.4
- scikit-learn >= 0.15

## Couple of pointers
- Data (audio files) are not pushed. Contact me if you need them. If you want to train with your own data, create a directory *data* under home having two subdirectories under it, i.e. *breathing* and *non_breathing*. Put your audio files or directories containing the audio files under the corresponding class. 

## To Do
- Hyperparameter Optimization
- (Optional) Implement scikit-learn-independent testing

## Contact
oguzhan.gencoglu@tut.fi

License: MIT
