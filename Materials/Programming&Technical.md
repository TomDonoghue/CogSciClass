# Programming / Technical Skills

In science, and also industry, programming and technical skills are very often the tools needed to get work done - to collect, process, analyze and visualize data. Mathematical skills can also be very useful, and will be a huge boost for a large number of research areas and jobs. Much of data processing and analysis relies on mathematical principles (in particular, statistics) and the more you know about these underlying principles, the better, and easier it will be. Machine learning (and AI in general) in particular, are in many ways areas of 'applied math'.

For programming, there are many possible languages one can use, and no simple answer as to what is best. Often, the best language depends on the task - some languages are designed for doing particular things. You can also compare the 'level' of a programming language - which is basically the abstraction: lower level languages are closer to machine code (more control), but take a bit more work, where as higher level languages are a bit more abstract, making them often easier to work with, although they may be slightly lower and less efficient. Here we will focus on Python - a popular high-level, general purpose programming language. In research, other high-level languages such as R and Matlab are also quite common, and (lower level languages) such as Java,  C, and C variants are also common across industry and research. 

## Python

Python is a very common, general purpose language - one of the most used programming languages in the world. As a general purpose language, it is build to be able to do many different things, and pretty good at them all. Python is open-source, meaning it is free, and you have access to all the code underlying the language. 

One of the main benefits of is a large community. Since so many people use Python, and share code, there is a lot of useful Python code available. Another benefit is the explicit guidelines - Python developers have and use a style guide that emphasizes writing code in an accessible way for human readers. 

There are two current main version of Python - Python2 and Python3. They are very similar, with a few bigger changes that warranted making a new version. Many things still use Python2 for historical reasons (legacy code), but at this point, if you are starting, I see no reason not to start straight into Python3 - as it's newer and the Python version of the future. 

### Resources for Python:

As a beginner, I recommend starting with CodeAcademy, since it is a good, simple, introduction to how the language works, and runs online. From there, get Python set up on your own computer (using Anaconda - see below), and work through one of the more advanced tutorials, running code on your own computer. Programming ultimately takes time, and lots of practice. There are some links with examples and programming tasks to practice with. Once you have a handle on the basics of the Python, the best way to keep working is to have some kind of a project to work on.

The official Python website (https://www.python.org/) also has a lot of good resources. Click on ‘Documentation’ to go to the official tutorials and help documents.

Python Resources:
- ‘Codecademy’ has some great beginner tutorials that don’t assume any prior programming knowledge, for Python, and also for many other programming languages. These tutorials run directly in the browser, so you don't have to set anything up on your computer. 
    - https://www.codecademy.com/

- A Byte of Python is a free introduction / tutorial / book for starting with Python.
    - https://python.swaroopch.com

- 'Learn Python the Hard Way' is another tutorial / book introduction to Python, focused on a hands-on, project based approach to learning Python, which I used and liked. However, there used to be a free version, which no longer appears to be the case, although you can still access a set of demo chapters. 
    - http://learnpythonthehardway.org/book/


If you are already familiar with programming in general, check out this 'Whirlwind Tour of Python'
- https://github.com/jakevdp/WhirlwindTourOfPython

Once you've started to get a feel for the language, if you want some problems to work on, try the following:
- The Python Challenge: http://www.pythonchallenge.com
- Project Euler: https://projecteuler.net

One of the best parts of Python is how much available resources there are. Below are links to collections of other resources that may be useful:
- Python Learning Resources: https://github.com/CodementorIO/Python-Learning-Resources
- Best Python Resources: https://www.fullstackpython.com/best-python-resources.html
- Hitchhiker's Guide to Python: http://docs.python-guide.org/en/latest/intro/learning/
- Quora, How to start learning Python: https://www.quora.com/How-should-I-start-learning-Python-1

### Managing Python: Anaconda & Jupyter Notebooks

Python is made up of the core (standard) library, and then lots of extra packages of code that add all kinds of other functionality to Python. To manage Python and it's packages, use Anaconda - it gives you a copy of Python, including a ton of the packages you need for scientific computing, and also a way to download and organize any new packages you might need. 

In addition to offering a way to manage Python, Anaconda comes with Jupyter Notebooks, a powerful tool for interactive programming with Python (http://jupyter.org).

Follow this link, and download Anaconda for your operating system. You will get a program called Navigator, from which you can launch Jupyter notebooks:
- https://www.continuum.io/downloads

### Scientific Python

Once you have the basics down, you will want to move on to using for scientific purposes. With Anaconda, you will have all the main packages you need for this - scipy, numpy, matplotlib, pandas, nltk, etc. To learn how to use these packages, you can follow along with a course I worked on at UCSD - Hands on Data Science (programming in Python for 'Data Science' is effectively the same as scientific programming). 

The materials from the course are here:
- https://github.com/COGS108
In particular, here are a set of quick tutorials (in Jupyter notebooks), including many links to other external resources:
- https://github.com/COGS108/SectionMaterials
Jake VanderPlass also has a great set of Jupyter notebook guides for data science / scientific computing:
- https://github.com/jakevdp/PythonDataScienceHandbook

### Coding Practices

As you start to get a handle on coding, try to make sure you are writing *good* code - that is, code that follows conventions and style guides, that is written cleary, with documentation, etc. All of this makes it much easier for yourself to keep track of what the code does, and how it works, and also makes it much easier to share code.

Style: Python has a specific and well developed style guide. Check it out, and use it to write code:
- PEP8: https://www.python.org/dev/peps/pep-0008/

Documentation: It's important to document code! One of the best ways to do so is with the numpy docs format:
- Numpy docs: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt


## Arduino / Robotics

If you are at all interested in robotics, then look into Arduino, who make micro-processor boards that can easily be used to make little robots with a variety of sensors and effectors. The most basic board is the Uno, about 25$ from Arduino directly or often cheaper from other stores (like Amazon) and there are also a lot of great ‘starter kits’ that come with a range of sensors and extra parts. Controlling Arduino's means writing code in the Arduino language, which is basically a variant of C. 
- https://www.arduino.cc/
