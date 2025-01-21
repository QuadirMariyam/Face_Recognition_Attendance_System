# Face Recognition Attendance System

A Face recognition Attendance System which names the user using using OpenCV, NumPy, and the Face recognition library introcued by Adam Geitgey in 2017 with an accuracy of 99.38%,  a machine learning based project, inspired by @krishnaik06.

To run -
  1. In Anaconda prompt, - $conda activate myenv
  2. $ spyder
  3. In Spyder, on the run section tap and press F5 To stop, press on the red button on the same section

Pre-requisites - In a folder -
  1. 2 images in a folder - training images
  2. a csv file - Attendance
  3. a python file - main
  4. a text file - requirements

How to use -
  1. Download VS Community Edition 2019 from Microsoft
  2. Check on the Desktop development with C++ box and install
  3. Download or Arrange the pre-requisites
  4. Inside Anaconda Prompt, create a conda environment with python 3.7 - $ conda create -n myenv python=3.7
  5. Change directories to the pre-requisite folder - $ cd ...
  6. Activate the env - $ conda activate myenv
  7. Check directory and verify - $ dir
  8. Install the libraries in requirements - $ pip install -r requirements.txt
In case of dlib wheeling error "encountered error while trying to install package - dlib" (in 2022 edition)
- Change the versions, cmake==3.25.2 and dlib==19.24.2 and pip install again

  9. Open Sypder by - $ spyder
  10. If spyder is not present install - $ pip install spyder
In case of metadata error " Preparing metadata (pyproject.toml) ... error error: subprocess-exited-with-error
× Preparing metadata (pyproject.toml) did not run successfully. │ exit code: 1 ╰─> [6 lines of output]

Cargo, the Rust package manager, is not installed or is not on PATH.
This package requires Rust and Cargo to compile extensions. Install it through
the system's package manager or via https://rustup.rs/

Checking for Rust toolchain....
[end of output]
note: This error originates from a subprocess, and is likely not a problem with pip. error: metadata-generation-failed

× Encountered error while generating package metadata. ╰─> See above for output"
- Deactivate the env by - $conda deactivate
- Install Spyder by - $pip install spyder
- Activate the env by - $conda activate myenv
- Run Spyder - $ spyder, In case not found, re-install spyder - $pip install spyder
- Run Spyder
- Follow Krish Naik video

# New Error - Bad memory Allocation
On searching, found out maybe due to high resolution of images, so Gemini gave a piece to attach before encoding pic

def resize_image(image, max_size=800): 
  height, width = image.shape[:2] 
  if max(height, width) > max_size: 
    ratio = max_size / float(max(height, width)) 
    new_height = int(height * ratio) 
    new_width = int(width * ratio) 
    image = cv2.resize(image, (new_width, new_height)) 
  return image

#Resize each image in your images list before finding encodings images = [resize_image(img) for img in images]

- - Runs Successfully -
