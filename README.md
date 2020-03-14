# OpenCV-inRange-Picker

This repository is an example code of cv2.inRange with trackbar that easy to see the preview in real-time

![alt text](https://github.com/earthsaharat/OpenCV-inRange-Picker/blob/master/inRange.gif "Demo")

## Installation

Download only file `inRange.py`

### Requirement
- Python3
- OpenCV
- NumPy

### Run
Run like a general python file

## Configuration

#### Change preview image
```python
org = cv2.imread('color.jpg')
```
Change `color.jpg` to your image that you want

#### Scaling preview image
```python
scale = 1
```
Change `1` to the scale that you want (scale up or down)

For example, if image size is 100x100
- scale = 2 -> image size is 200x200
- scale = 1 -> image size is 100x100
- scale = 0.5 -> image size is 50x50
- scale = 0.2 -> image size is 20x20

#### Separate config menu from the preview
```python
configWindowName = 'img'
```
Change `'img'` to another name (any name)


