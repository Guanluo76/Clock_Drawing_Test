# Clock Drawing Test

This is a [Clock Drawing Test](https://en.wikipedia.org/wiki/Executive_dysfunction#Clock_drawing_test) scoring system implemented with html, css, javascript and python, which is based on ajax + django design framework and mvc design pattern.

## <span id="intro">Introduction</span>

The clock test is a simple, high-accuracy and culturally relevant deafness screening test that comprehensively reflects cognitive function, and can be used as an early screening tool for examining senile dementia.

Freehand drawing of timepieces is a complex behavioral activity. In addition to spatial construction techniques, many knowledge functions are required to participate, involving memory, attention, abstract thinking, design, layout, use, numbers, calculations, time and space orientation concepts, and operation order. In all, A variety of cognitive functions are in need.

The clock test has a variety of score tables. The system uses a 4-point system, which are:

- A closed circle

- Scales located inside the circle and evenly distributed

- Numbers evenly distributed in the circle and arranged in 1 - 12 order

- The hour and minute hands pointing to the correct time (specified by the tester)

## <span id="depend">Dependencies</span>

- [OpenCV](https://opencv.org/) :

`pip install opencv-python`

- [Numpy](https://numpy.org/) :

`pip install numpy`

- [Django](https://www.djangoproject.com/) :

`pip install Django`

Make sure you can run the following statements in your Python 3 shell:

```
import numpy
import cv2
import django
```

## <span id="method">Using Method</span>

- Config the dependencies in need

You should make sure having installed python3, django, opencv and numpy.

- Download this repo

One way, download this repo directly, the other, use the command : ```django-admin startproject CDT``` to build a django project and copy all folers and files into it.

! Note : Don't forget to copy the backend part [https://github.com/SPiCaRiA/Clock-Drawing-Test](https://github.com/SPiCaRiA/Clock-Drawing-Test) to the judge folder.

- Enter the follow command in cmd

```python manage.py runserver 0.0.0.0:8000```

Enter this to start the local server.
