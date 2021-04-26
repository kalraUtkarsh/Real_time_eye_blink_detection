# Real_time_eye_blink_detection
This is a real time eye blink detection project using openCV and dlib
The main landmarks for the face have been taken using the dat file 'shape_predictor_68_face_landmarks.dat' and using the dlib.get_frontal_face_detector() in dblib.
To run this project all you need is `OpenCV` installed for your version of Python.
`dlib` installed and working.
You need to put the file `shape_predictor_68_face_landmarks.dat` in the same directory as the code file.
You can downlaod the `shape_predictor_68_face_landmarks.dat` file from :https://drive.google.com/file/d/1sh1gXPdTgFl8D4B_nUSQ6_-yoqnl03Pn/view?usp=sharing
Now simply just run the `Blink.py` file and see the magic happen.


Here are some Image examples.
This is when you blink
![image](https://user-images.githubusercontent.com/42469374/116015540-47590200-a642-11eb-9647-3c6e9841f86d.png)


When your eyes are open you can still see the blink count in green color.
![image](https://user-images.githubusercontent.com/42469374/116015599-82f3cc00-a642-11eb-9fa2-2c45de48c199.png)


When you have closed your eyes for more than 2sec, It will show 'Alert!' in red color
![image](https://user-images.githubusercontent.com/42469374/116015626-99018c80-a642-11eb-94f7-8f53b1d74355.png)

In case of any questions, please contact me.
email: u.kalra@innopolis.university
telegram: kalra.Utkarsh
