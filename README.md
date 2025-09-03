# This repsoitory is for the C++ ToolChain


Main VIdeo:
https://www.youtube.com/watch?v=bvxpzwHN1mo&list=PLpQIfX0Z22sYiMAMiH-zakRnEdJW7gcub&index=1&pp=iAQB

VS Code:
https://youtu.be/U2SfDXixKjY?list=PLpQIfX0Z22sYiMAMiH-zakRnEdJW7gcub

xCode: https://www.youtube.com/watch?v=xNkauChZV64&list=PLpQIfX0Z22sYiMAMiH-zakRnEdJW7gcub&index=2&pp=iAQB

by Bill Weinman

<hr>

# Ubuntu 24.04
In order to install the C++ on ubuntu, you will need the run the following commands:

## Installing GCC 
```bash
sudo apt update
sudo apt install buid-essential
#sudo apt install gdb ddd
gcc --version
g++ --version
```
## Format Library
The format library is added in C++ 20 and should be avaialible in releases after 20. In Ubuntu 24.04, the C++ (GCC) tools version is 14.2.0
```
$ g++ --version
g++ (Ubuntu 14.2.0-4ubuntu2~24.04) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

Older tools may need to install the format library from
```bash
fmt.dev
```
Follow the web site instructions to install this library on your system.
