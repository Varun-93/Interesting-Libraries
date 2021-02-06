# Interesting-Libraries-Packages
> Python Packages are a set of python modules, while python libraries are a group of python functions aimed to carry out special tasks. In this article, we are going to discuss some of the interesting libraries and packages.

**NOTE**: Some of these code may not work in **_Python 2_**. Hence I strongly recommend you to try them in **_Python 3_**.

## Table of contents
* [Pillow](#pillow)
* [Howdoi](#howdoi)
* [Wikipedia](#wikipedia)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)


## Pillow
Pillow is a modern version of PIL – Python Image Library. A trusted library while working with images or any type of image format.
It adds image processing capabilities to your Python interpreter.
Features Of Pillow:
* Using Pillow, you can not only open and save images but also influence the environment of images as well.
* Pillow supports a lot of file types such as PDF, WebP, PCX, PNG, JPEG, GIF, PSD, WebP, PCX, GIF, IM, EPS, ICO, BMP, and many others as well.
* Pillow supports a collection of image filters – FIND_EDGES, DETAIL, SMOOTH, BLUR, CONTOUR, SHARPEN, SMOOTH_MORE, and others.

Pillow can be installed using **pip** :

```
$ python3 -m pip install --upgrade pip
$ python3 -m pip install --upgrade Pillow
```

One can find more about this library from here: https://pypi.org/project/Pillow/




## Howdoi
Stuck on a coding problem? Wish to visit StackOverflow without leaving the terminal? With howdoi, you can do it!
It provides instant coding answers via the command line and without opening the browser and read through blogs.

Howdoi answers all sorts of queries:

```
$ howdoi print stack trace python
> import traceback
>
> try:
>     1/0
> except:
>     print '>>> traceback <<<'
>     traceback.print_exc()
>     print '>>> end of traceback <<<'
> traceback.print_exc()
```

Howdoi can be installed using **pip** :

```
$ pip install howdoi
```

One can find more about this library from here: https://pypi.org/project/howdoi/




## Wikipedia
One can use th Wikipedia module to fetch a variety of information from the Wikipedia website.
Search Wikipedia, get article summaries, get data like links and images from a page, and more, this library wraps the official Wikipedia API.

Use the incessant flow of knowledge with Python for daily needs.

```
$ import wikipedia
$ wikipedia.search("Barack")
> [u'Barak (given name)', u'Barack Obama', u'Barack (brandy)', u'Presidency of Barack Obama', u'Family of Barack Obama', u'First inauguration of Barack Obama', u'Barack Obama presidential campaign, 2008', u'Barack Obama, Sr.', u'Barack Obama citizenship conspiracy theories', u'Presidential transition of Barack Obama']
```
