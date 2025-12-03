# Discleamer
It is an unofficial LaTeX template for the theses of the graduate İzmir 
Institute of Technology students. This template is for assistance only, and the 
repository contributor(s) assumes no liability. 
**There are still bugs and mistakes!**

# Installation Guide (Tested on Ubuntu and TeXstudio)
This LaTeX template has been tested on **Linux (Ubuntu)** and works properly 
when the steps below are followed:

1. **Install LaTeX Distribution:**
For Ubuntu, the most reliable installation is:
`sudo apt install texlive-full`

2. **Install Texstudio:**
You may use TeXstudio as your LaTeX editor: `sudo apt install texstudio`

3. **Bibliography Tool -> biber:**
This template uses biber for bibliography management.
In TeXstudio, configure it as follows:
    - Options -> Configure Texstudio -> Build
    - Set **Default Bibliography Tool** to **biber**

# Usage
You can edit the allowed area in the `main.tex` file. You can create a new TeX 
file in the chapters directory, and input in the `main.tex` file just as 
`guide.tex`. The `guide.tex` file shows some examples of usage of some LaTeX 
essencials. Also, check the `preferences.tex` file, you need to set the 
configurations for your thesis.

# Credits

## Contributors
- Nuri Furkan Pala
- Ege Yiğit Çelik
- Ersin Çine
- Büşra Çalmaz

## Additional Credits
Some parts of the templates are obtained from 
[a repository of Ronny Majani](https://github.com/ronnymajani/iyte-master-thesis-template).

The example image is an artificial intelligence image generated using 
[craiyon.com](https://www.craiyon.com/).

## External Licences
The MIT License (MIT) Ronny Majani

Copyright (c) 2018 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
