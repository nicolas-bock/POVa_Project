# POVa Project: Facial recognition from RGB-Depth images (identification)

## Description
This project consist of a jupyter notebook divided in severals parts:

1. Data processing.
2. Face detection using existing detectors, like OpenCV and MTCNN.
3. Face alignment based on detected facial features
4. Training and evaluation of a CNN to identify faces.

## Dataset
For the data, we used the following dataset:

``https://vis-www.cs.umass.edu/lfw/``

There are more than 13.000 face images of 5749 different personalities in total.

## Installation
### Steps
1. **Clone the Repository**

   ```bash
   git clone https://github.com/nicolas-bock/POVa_Project.git
   cd POVa_Project
   ```

2. **Set Up a Virtual Environment**

   ```bash
   pip install --user virtualenv
   virtualenv -p python3 pova
   source ./pova/bin/activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

### Requirements
All required python libraries are listed in the ``requirements.txt``.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
