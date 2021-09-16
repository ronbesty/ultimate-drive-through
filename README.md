# Ultimate Drive Thru
Ultimate Drive Thru is a python application served as a replacement for traditional drive thru solution. It uses Natural language processing and google speech API to completely automate the ordering process.

### Features!

  - Converts speech from microphone into a valid order and places it in the database
  - Options for setting up database connection provided in Menu
  - Easy to use intuitive GUI





### Softwares used

Drive thru uses a few open source projects to work properly

- [SpeechRecognition](https://pypi.python.org/pypi/SpeechRecognition/) - Library for performing speech recognition, with support for several engines and APIs, online and offline.
- [PyQt](https://pypi.python.org/pypi/PyQt4) - Provides Python wrapper to use Qt Windowing framework.
- [PyCharm](https://www.jetbrains.com/pycharm/) - Text Editor of choise. Used under COMPLIMENTARY LICENSE

__Installation__

We will use cx_Freeze package to create Linux and Windows executable files.

__Linux__

```sh
$git clone https://github.com/vyshark/ultimate-drive-thru.git
$cd ultimate-drive-thru
$python setup.py build
```
A build/exe.linux* folder will be created in the directory and the executable can be found inside.
U can then move it to your $PATH .
Additionally u may create .desktop files to launch it from your desktop.

__Windows__
>Install the executable. 

__Run manually__

```sh
$python UserInterface.py
```

