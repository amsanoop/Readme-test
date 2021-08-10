# Ai-Bots Studio
[![GitHub license](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://raw.githubusercontent.com/tesseract-ocr/tesseract/master/LICENSE)

![screenshot](./imgs/studio.PNG)

## About

This package contains a Robotic Process Automation (RPA) Studio which enables you to build and manage software Bots which mimicks humans actions interacting with digital systems and software. Just like humans, RPA robots can do things like extracting details on a screen, complete the mouse clicks or keystrokes, navigate through systems, identify and extract data from desktop or web applications, and perform varius other actions. Once trained RPA Bots can do these tasks much faster and consistently than humans

## Running Aibots Studio

You can run the Ai-Bots Studio by opening the [source code](https://github.com/aibotstechrepo/AiBotsStudio) in a compatible IDE, preferably [Microsoft Visual Studio](https://visualstudio.microsoft.com/downloads/):

Once opened you can run the following startup file to launch the application:

    AiBotsRPA

Ai-Bots Studio require .NET 4.5 or above to run*


## Examples

- [Performing Keystrokes](https://github.com/amsanoop/Readme-test/blob/main/Examples/keystrokes.abt) Demonstration of entering a text in a notepad application
- [calculator.py](https://github.com/willmcgugan/textual/tree/main/examples/calculator.py) A "clone" of the MacOS calculator using Grid layout
- [code_viewer.py](https://github.com/willmcgugan/textual/tree/main/examples/code_viewer.py) A demonstration of a tree view which loads syntax highlighted code
- [grid.py](https://github.com/willmcgugan/textual/tree/main/examples/calculator.py) A simple demonstration of adding widgets in a Grid layout
- [grid_auto.py](https://github.com/willmcgugan/textual/tree/main/examples/grid_auto.py) A demonstration of automatic Grid layout
- [simple.py](https://github.com/willmcgugan/textual/tree/main/examples/simple.py) A very simple Textual app with scrolling Markdown view


## Support

Before you submit an issue, please review **[the guidelines for this repository](https://github.com/tesseract-ocr/tesseract/blob/master/CONTRIBUTING.md)**.

For support, first read the [documentation](https://tesseract-ocr.github.io/tessdoc/),
particularly the [FAQ](https://tesseract-ocr.github.io/tessdoc/FAQ.html) to see if your problem is addressed there.
If not, search the [Tesseract user forum](https://groups.google.com/g/tesseract-ocr), the [Tesseract developer forum](https://groups.google.com/g/tesseract-dev) and [past issues](https://github.com/tesseract-ocr/tesseract/issues), and if you still can't find what you need, ask for support in the mailing-lists.

Mailing-lists:
* [tesseract-ocr](https://groups.google.com/g/tesseract-ocr) - For tesseract users.
* [tesseract-dev](https://groups.google.com/g/tesseract-dev) - For tesseract developers.

Please report an issue only for a **bug**, not for asking questions.

## License

    The code in this repository is licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

**NOTE**: This software depends on other packages that may be licensed under different open source licenses.

Tesseract uses [Leptonica library](http://leptonica.com/) which essentially
uses a [BSD 2-clause license](http://leptonica.com/about-the-license.html).

## Dependencies

Tesseract uses [Leptonica library](https://github.com/DanBloomberg/leptonica)
for opening input images (e.g. not documents like pdf).
It is suggested to use leptonica with built-in support for [zlib](https://zlib.net),
[png](https://sourceforge.net/projects/libpng) and
[tiff](http://www.simplesystems.org/libtiff) (for multipage tiff).

## Latest Version of README

For the latest online version of the README.md see:

https://github.com/tesseract-ocr/tesseract/blob/master/README.md
