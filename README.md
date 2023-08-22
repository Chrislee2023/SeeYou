# Face Info
Face Info is an implementation of facial recognition, detection of facial attributes (age, gender, emotion and race) for python.
The repository provides a script to run Face Info with the webcam or by entering the path of an image.
This implementation allows recognition of multiple faces and the registration of new users for facial recognition.

# How to install:
<pre><code>pip install -r requirements.txt </code></pre>

# How to run:
The code is tested in python 3.7.8 and macOS Catalina
<pre><code>python3 Face_info.py --input webcam </code></pre>

running over an image
<pre><code>python3 Face_info.py --input image --path_im data_test/friends.jpg </code></pre>

# Add new faces to the database (facial recognition)
You can add new users to the faces database simply by adding the person's photo in the **images_db** folder, for the registry to work correctly, only the person of interest should appear in the photo.
