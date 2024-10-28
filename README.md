# Object Detection Pipeline
Complete tutorial on building a object detection system
The aim of this tutorial is to build all of the componants required to build a objct detection system. The main thread will be to build a system based on YOLO 11 on custom data, there will also be branches to incorporate other methods for detecting objects in images.
There will be a branch to deal with multimodel models such as florence2 which allow the user to pose plain text queries concerning and image.
Whenever I use {} this means that the user should remove this code including the {} and replace this with their code, e.g. At the command prompt type python -m venv {the name that you require for your venv} -> At the command prompt type python -m venv .venv

# Setup GITHUB
1. My first step is always to setup and clone a github repositry for the project.
2. Once I create a github repositry with a readme and mit licence the next step is to edit the gitignore file to include and file that uses the format .objectDetect (you can use just venv with no need to change the gitignore file but this way I can be sure what environment I'm in).
3. Clone the repositry to your local computer.
4. cd into directory

# Setup Virtual Environment
I will be using venv but use whatever virtual environment you prefer, just use one.
1. Navigate to the project directory.<br><br> ![addressBar1](https://github.com/user-attachments/assets/84af51f9-a805-439f-85a5-94498a3daf57) <br><br><br>
3. In the andress bar for windows explorer type cmd and hit 'enter'<br><br>![addressBar2](https://github.com/user-attachments/assets/7290562b-7f91-4821-ab5c-31b5066340df)<br><br><br>
5. At the command prompt type python -m venv {.objectDetect}<br><br>![venv](https://github.com/user-attachments/assets/17de97ff-1851-4916-b09a-38efd91de0cb)<br><br><br>
7. Acivate the venv {.objectDetect}\Scripts\activate<br><br>![activate](https://github.com/user-attachments/assets/d8007242-5d96-46ad-a761-b602d4434155)<br><br><br>


# Download a Dataset For Training

# Create a Dataset For Training

# Train The YOLO11 Model on The Custiom Dataset

# Evaluate The Trained Model


# Deploy The Model