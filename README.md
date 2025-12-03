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
