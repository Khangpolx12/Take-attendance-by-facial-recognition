# Take-attendance-by-facial-recognition
Xử lí ảnh số

BÀI TẬP CUỐI KÌ

# Take attendance by facial recognition
Attendance based on Face Recognition using Python  and OpenCv  

### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### What steps you have to run project??

- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.
- To run the 'Check registered student' button, you need to log in: username: khale, password: khale123.

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model for train a model click on `Train Image` button.
- It will take 5-10 minutes for training.
- After training click on `Automatic Attendance` ,it can fill attendance by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database. But currently, due to time constraints, understanding the database is not good and there are many unresolved errors, so I cannot use this feature. I hope you understand.

### Screenshots

### Basic UI
<img src="https://github.com/Khangpolx12/Take-attendance-by-facial-recognition/Take-attendance-by-facial-recognition/Screenshot(1).png">

### When pressing a button Take image
<img src="https://github.com/Khangpolx12/Take-attendance-by-facial-recognition/Take-attendance-by-facial-recognition/Screenshot%20(2).png">

### When pressing a button Train image
<img src="https://github.com/Khangpolx12/Take-attendance-by-facial-recognition/Take-attendance-by-facial-recognition/Screenshot%20(3).png">

### When it Recognises me when i pressing a button Automatic Attendance
<img src="https://github.com/Khangpolx12/Take-attendance-by-facial-recognition/Take-attendance-by-facial-recognition/Screenshot%20(4).png">


### Manually attendance filling UI error that cannot be resolved

### When pressing a button Check registered student
<img src="https://github.com/Khangpolx12/Take-attendance-by-facial-recognition/Take-attendance-by-facial-recognition/Screenshot%20(6).png">



### Notes
- It will require high processing power(I have 8 GB RAM)
- Noisy image can reduce the accuracy, so quality of images should be good.


