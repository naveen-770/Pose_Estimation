## Pose_Estimation and Human Activity Recognition (HAR)


**Steps to Install**

1. Download this repo and extract it https://github.com/ildoonet/tf-pose-estimation       
$ git clone https://www.github.com/ildoonet/tf-pose-estimation
2. Download Swig for your Operating System and extract it.
3. Add Swig to your Path.      
$ cd tf-pose-estimation       
$ pip3 install -r requirements.txt
$ cd tf_pose/pafprocess
$ swig -python -c++ pafprocess.i && python setup.py build_ext --inplace      
$ cd ..        
4. Go to this link http://www.mediafire.com/file/qlzzr20mpocnpa3/graph_opt.pb and download the 
graph_opt file.
5. Open the prompt and run file
$ python filename.py


This github repository consist of basic pose estimation and 5 HAR (Human Activity Reognition) activities such as Smoker Detection, Mountain Pose Checker, Plank position checker, Fall Detector and People Counter.


all.py contains all the files.        
Seperate files are also given.
