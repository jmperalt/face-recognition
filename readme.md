Step 1: Download python 3.7.0 https://www.python.org/downloads/release/python-370/
Step 2: When the installation complete, click the "Install Certificate.command"
Step 3: Install homebrew in terminal https://brew.sh/
Step 4: Open the project, and install the "requirements" file
Step 5: When there is an error installing the requirements such as the "pip install face_recognition==1.2.2", 
install the appropriate package, and make sure the environment is 3.7.0.
Note: I ran into problem, and I troubleshoot. I run the following command in order
1. pip install cmake
2. pip install dlib
3. pip install face_recognition==1.2.2

Commiting your work to git repository:
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jmperalt/face-recognition.git
git push -u origin main