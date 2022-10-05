
# **The simple python tutorial for beginners**




```python
import datetime
from random import randint
months = ['January','February','March','April','May','June','July','August','September','October','November','December']
dofweeks = ['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']

year = datetime.date.today().year

month = int(datetime.date.today().month)

day = datetime.date.today().day

weekday = int(datetime.date.today().weekday())

print(f'Today it is currently {dofweeks[weekday]} {months[month - 1]} {day}, {year}')

```
>Output: Today it is currently Monday October 3, 2022

What you just saw there is a simple python script that shows you the day today.

Now it may not look like the right day to you but because this md file cannot print correctly. But python can! Now, Before you learn the basics, why should you learn python in the first place?

* It's easy and friendly for beginners
* It's a high level programming language, so you can do useful things with the language
* Once you learn python you can easily learn any other language.

Now before you start the tutorial, You will need to download a python text editor. Some choices are:
>* [VScode](https://code.visualstudio.com/download)
>* [PyCharm](https://www.jetbrains.com/pycharm/download/#section=windows)
>* Online text editors like [Programiz](https://www.programiz.com/python-programming/online-compiler/), Or [Online-Python](https://www.online-python.com/). 

In my opinion, I would use PyCharm. But before you pick, here is a graph on each editor.

| Editor | Reason to use |
| --- | --- |
| VScode |  Lightweight |
| PyCharm |   |
| Programiz or Online-Python |   |


Once you open or install these editors, create a new project. I will go through the process of making a new project in each editor, so scroll down until you see your editor of choice pop up.


## Setting Up PyCharm

Now, The process for setting up PyCharm is easy. Click the link I gave you.




| Command | Description |
| --- | --- |
| print(" ") | Print line in prompt. Add quotation marks to print whatever you want. |
| input(" ") | Ask the user for input. Add quotation marks to print whatever you want. |
