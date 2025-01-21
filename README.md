# Face_Recognition_Attendance_System
A Face recognition Attendance System which names the user using face recognition library, a machine learning based project, inspired by @krishnaik06

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
  9. In case of dlib wheeling error "encountered error while trying to install package - dlib" (in 2022 edition)
- Change the versions, cmake==3.25.2 and dlib==19.24.2 and pip install again
  
  11. Open Sypder by - $ spyder
  12. If spyder is not present install - $ pip install spyder
  13. In case of metadata error " Preparing metadata (pyproject.toml) ... error
      error: subprocess-exited-with-error

  × Preparing metadata (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [6 lines of output]

      Cargo, the Rust package manager, is not installed or is not on PATH.
      This package requires Rust and Cargo to compile extensions. Install it through
      the system's package manager or via https://rustup.rs/

      Checking for Rust toolchain....
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
error: metadata-generation-failed

× Encountered error while generating package metadata.
╰─> See above for output" 
- Deactivate the env by - $conda deactivate
- Install Spyder by - $pip install spyder
- Activate the env by - $conda activate myenv
- Run Spyder - $ spyder, In case not found, re-install spyder - $pip install spyder
- Run Spyder
- Follow Krish Naik video
