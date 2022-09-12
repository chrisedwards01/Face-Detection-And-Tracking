First make sure you install these packages : dlib and face_recognition

pip3 install dlib 
pip3 install face_recognition
Also install pickle on your pi device

Now we have 2 files ie

embedding.py: In this step, we will take images of the person as input. We will make the face embeddings of these images.
recognition.py: Now, we will recognize that particular person from the camera frame.

Since i used this in raspberry pi i gave the default camera as pi camera 
Now open the py files in thonny IDE

Step 1 - At first run the embedding file and take few naps (5in this case) and then they are saved i nform of pickle file.
Step 2 - Now run recognition which should be able to detect your face

