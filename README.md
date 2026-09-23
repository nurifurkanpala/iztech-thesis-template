# Disclaimer
This is an **unofficial** LaTeX template for graduate theses at İzmir Institute of Technology (IZTECH). **It has not yet been officially approved or adopted by the Graduate School.** 

This template is provided for guidance and convenience only; the contributor(s) assume no liability for thesis formatting rejections. **There may still be bugs, formatting discrepancies, or errors.** Always cross-check your final document against the official thesis writing guidelines.

# Installation Guide (Tested on Ubuntu and TeXstudio)
This LaTeX template has been tested on **Linux (Ubuntu)** and works properly when following these steps:

1. **Install LaTeX Distribution:**
   For Ubuntu, the most complete installation is:
   `sudo apt install texlive-full`

2. **Install TeXstudio:**
   You may use TeXstudio as your editor:
   `sudo apt install texstudio`

3. **Configure Bibliography Tool (Biber):**
   This template uses **Biber** via `biblatex` for reference management.  
   In TeXstudio, configure it via:
   - Options -> Configure TeXstudio -> Build
   - Set **Default Bibliography Tool** to **Biber**

# Usage
- Edit the designated metadata and settings in `preferences.tex` (e.g., title, author, supervisor, department).
- Work within `main.tex` to structure your thesis. 
- To add a new chapter, create a `.tex` file in the `chapters/` directory and include it in `main.tex` using `\input{...}` (similar to `guide.tex`).
- Refer to `guide.tex` for practical examples of core LaTeX essentials (tables, figures, equations, and citations).