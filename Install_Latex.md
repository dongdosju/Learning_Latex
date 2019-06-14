# Latex 

## 1. Install Compliers [(Miktex)](https://miktex.org/)
- [Window](https://miktex.org/howto/install-miktex)
- [Ubuntu](https://miktex.org/howto/install-miktex-unx)

## 2. Install Editor:
### 2.1. TexMaker (Recommend)
  + Windows: 
  [Download](http://www.xm1math.net/texmaker/) --> Install.
  + Linux:
    ```sh
    $ sudo apt-get install texmaker
    ```
### 2.2. Sublimetext (Windows)
####  1. Download and Install [SublimeText](https://www.sublimetext.com/3) .
####  2. Install PDF Viewer [SummatraPDF](https://www.sumatrapdfreader.org/download-free-pdf-viewer.html).
####  3. Setting Sublime Text and Summatra PDF:
  - Add SumatraPDF to the path: http://economistry.com/2012/10/first-pdf-sublime-text-2-latex/
    - For Sublime to open SumatraPDF for you when you build your PDF, we need to add the PDF viewer to your path. 
    - Adding SumatraPDF to your path allows your programs to open SumatraPDF without having to know exactly where you installed it. To add SumatraPDF to your path, right-click Computer from the desktop or the Start menu. 
    - Choose the “Properties” option. 
    -  Select “Advanced system settings” from the menu on the left. 
    - Choose the “Advanced” tab and click the “Environmental Variables…” button near the bottom. 
    - In the “System variables” section, click on the variable named “PATH” and click the “Edit…” button.
    - Place your cursor at the end of the text in the “Variable value:” field, add a semicolon, “;”, and enter the path to SumatraPDF. 
    - For me, the path was “C:\Program Files (x86)\SumatraPDF”. 
    - Click “OK” to accept your changes.

  - Install package control for [Sublime](https://packagecontrol.io/installation#st3)
  - Inverse Search: In Summatra PDF, Open Settings/Options... from menu. Enter the following command into the box:
    *"C:\Program Files\Sublime Text 3\sublime_text.exe" "%f:%l"*
    
## 3. Resource for Latex:
###  * Write Latex Online:
  - [Overleaf](https://www.overleaf.com)
  - [ShareLatex](https://www.sharelatex.com/)
  
  - [Firgure for Latex](http://www.texample.net/tikz/examples/)
  - [Tex stackechange](https://tex.stackexchange.com/)
  - [Create table for latex(Tables Generator)](http://www.tablesgenerator.com/)
 
## 4. Tutorial:
  - Latex tutorial with Vu Huu Tiep:
    - https://www.youtube.com/watch?v=_xR7eel_Q80&list=PLlsF2nDmyL7msihnebzII_KVWy6URxDfp&index=1
    - https://www.youtube.com/watch?v=y6IUHvzeyVI&index=3&list=PLlsF2nDmyL7msihnebzII_KVWy6URxDfp
  - https://www.latex-tutorial.com/tutorials/  
  - [Latex with TexMaker (Recomment)](https://www.youtube.com/watch?v=SoDv0qhyysQ)
  
## 5. Latex Template:
  - IEEE Conference Template: 
    - https://www.ieee.org/conferences/publishing/templates.html
    - https://www.overleaf.com/blog/ieee-templates-2014-05-13

## --- REFERENCES---
[1] https://github.com/tiepvupsu/LearningLatex
[2] https://dzone.com/articles/installing-latex-ubuntu
