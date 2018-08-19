************** Image Morphing Detection**************
Auther: H.M.S.U.Abeyrathne, 
Faculty of Information Technology, 
University of Moratuwa
For Team SQUAD --> Image Forgery Detection System
(2018)

For proper functionality

(01)	Make sure that Dlib facial landmark detection library has been installed to the anaconda environment in your PC. For that, open your command prompt and give billow pip command.
conda install -c conda-forge dlib=19.4  
 
(02)	If you are not using Anaconda use below command.
pip install dlib  

(03)	To identify faces and landmarks “haarcascade_frontalface_default.xml” and “shape_predictor_68_face_landmarks.dat” files must be in the same directory where the program files are located.

(04)	A dataset has been provided with the file. Feel free to feed any facial image to the system. Non_facial Images will be not working. Make sure that all the feeding images are in jpg format.

(05)	Copy the “Image_morphig_detection” folder to “C:” directory of your PC. That folder helps to keep generated results by the system in its sub folders.
