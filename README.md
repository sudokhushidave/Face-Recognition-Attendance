# Biometrics Project: Simple Face Recognition 
In my project, I am focusing on the simple way in which an algorithm detects and recognises faces. The working of the project is as follows:
We Run the program and firstly, it opens the Webcam to capture the image of the face that is to be recognised. Following this, after some backend work, it tells us who the face belongs to. The only problem with the system is that the face might not necessarily be of the person it claims to be, as it recognises based on the Face Encoding numbers.
### Back-end working:
The webcam takes a picture of the face that is to be recognised, and our program converts the face into 128 numbers of Face Encoding. These 128 numbers are obtained from different facial features like face contouring etc.
On the other hand, we have a few datasets, all of which are faces that are converted to Face Encoding numbers. 
After the webcam takes the picture, it converts the image to Face Encoded numbers and then compares it to each of the datasets that we have. Whichever dataset has the least difference with the Captured image, is shown to be the result. 
This way, our program detects and recognises faces.
