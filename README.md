# Robotics & Vision Toolboxes for Python

[IEEE RAS School Reproducible Research Performance Evaluation and Benchmarking in Robotics](http://www.reproducibleroboticsresearch.rocks)

## Lecturers

<img src="https://avatars.githubusercontent.com/u/21215791?v=4" alt="Jesse" width="200"/> <img src="https://avatars.githubusercontent.com/u/11801682?v=4" alt="Peter" width="200"/>


* [Jesse Haviland](https://github.com/jhavl)
* [Peter Corke](https://github.com/petercorke)


## Program

### Lecture

This session will give you an introduction to some Python toolboxes that make it easy to model and simulate quite complex robotic and robotic vision systems.
We will cover the following topics:

* transforms, quaternions and all that stuff (Peter), 8 mins
* robot manipulator arms; cameras (Peter), 8 mins
* cameras (Peter), 4 mins
* Swift - a fast browser-based simulator (Jesse), 20 mins

A [paper at the most recent ICRA](https://ieeexplore.ieee.org/document/9561366) gives a gentle introduction to the Toolboxes and our design philosophy.

PDF slides available here...

### Hands-on workshop

We provide Jupyter notebooks that you can run with zero-install on your computer (apart from the Swift simulator which can't work with CoLab).  These reinforce the material covered in the lecture.

* `icra2021.ipynb`  this takes you through core features of spatial mathematics and arm robots
* `mobile.ipynb` this takes you through some of the capabilities of the mobile robot component of the Robotics Toolbox
* Swift??
* `visualservo.ipynb` is an example of image-based visual servoing of a manipulator arm.  It is for you to complete, but we have sketched out some of the solution.

## How to get started with the code

### Local install

Install conda following instructions here https://docs.conda.io/en/latest/miniconda.html

```
// Make a new conda env
conda create -n 'ws-rtb' python=3.9

// Activate the new conda env
conda activate ws-rtb

// Install the toolbox and deps
conda install -c conda-forge roboticstoolbox-python==0.11.0

// Install jupyter notebook 
conda install -c conda-forge notebook

// Clone this repo to operate locally
git clone https://github.com/jhavl/ws-rtb.git
```

### Using CoLab
