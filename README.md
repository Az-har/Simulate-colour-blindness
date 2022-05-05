# Simulate Colorblindness and Correct Colors for People with Colorblindness


This Script simulates images based on how people with colorblindness would perceive it naturally. You can also vary the degree of colorblindness for simulating. This script can also be used to correct images, making differenciation of certain colors in an image easier for people with colorblindness.



## Installation

### Downloading the script

Go to the directory of your choice in terminal, and run the command below.
```shell
git clone https://github.com/Az-har/Simulate-colour-blindness.git
```
### Installing dependencies

To run this script, you need to install three libraries for python. Use pipto download PIL, Numpy and OpenCV.
```shell
sudo pip install Pillow numpy opencv-python
```

### Verifying the installation

Once you have successfully downloaded the scripts, and installed the dependencies, we can verify the installation.
The *~/Examples_Check/* folder contains a sample image containing a number of Ishihara plate images. 
We want to run the script on this example image and see if everything is working fine.

```shell
# Go to the directory where you downloaded the scripts.
cd <dir where scripts are downloaded>/Simulate-Correct-Colorblindness

# Now run the examples script.
python run_examples.py
```
This will run all the available algorithms on the example image,
and save the processed images in the *Examples_check/* directory,
