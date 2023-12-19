# Image-Morphing
### Overview
This project focuses on image morphing, a technique that seamlessly transforms one image into another through a series of intermediate frames. The key innovation lies in the use of the Delaunay triangulation algorithm, implemented using a highly efficient divide and conquer approach, to achieve fast and accurate triangulation of key points on the source and destination images.

### Getting Started
1. Clone the repository.
```
git clone https://github.com/Harsh290803/Image-Morphing.git
```
2. Install the required modules.
```
pip install -r requirements.txt
```
3. Add two JPG images in the *input* folder with the names `source.jpg` and `target.jpg` respectively.
4. Open `main.ipynb` and run all the cells.
5. See the output `movie.gif` in the *output* folder.

### Demo
![demo](output/movie.gif)