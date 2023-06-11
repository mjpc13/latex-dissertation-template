# Latex Dissertation Template

This is a public latex template repository to write dissertations. It complies with the [visual identity of Coimbra University](https://www.uc.pt/identidadevisual). It was designed for the Faculdade de Ciências e Tecnologias da Universidade de Coimbra, but it can be adapted. In you check the generated sample PDF in the [github pages](https://mjpc13.github.io/latex-dissertation-template/) of this repository. The complete documentation can be found on the [Wiki Pages](https://github.com/mjpc13/latex-dissertation-template/wiki).

## Getting Started

To get started, simply click on the **"Use this template"** (**DON'T FORK THE REPOSITORY UNLESS YOU WANT TO CONTRIBUTE!!!**) button on the repository page to create a new repository based on this template. This feature allows you to easily fork the project, creating your own copy that you can modify and customize without affecting the original template. It provides a clean starting point for your dissertation, saving you valuable time and effort.

### Overleaf

To start using the latex-dissertation-template in Overleaf, follow these steps:

1. Download the repository by clicking on the "code" button and selecting "Download ZIP". This will download a compressed file containing all the template files to your local machine.
2. Open Overleaf in your web browser and log in to your account (or create a new account if you don't have 
3. Once logged in, click on the "New Project" button on the top left corner of the Overleaf 
4.In the "New Project" menu, select the "Upload Project" 
5. Choose the downloaded ZIP file from step 1 and upload it to Overleaf. Overleaf will automatically extract the contents of the ZIP file and create a new project based on the template.

You can now start working on your dissertation using the template in Overleaf. The files and folders from the template will be available in the left-hand file browser pane, and you can edit them using the built-in LaTeX editor.

By following these steps, you can quickly set up the latex-dissertation-template in Overleaf and leverage its collaborative features and online editing capabilities for a seamless writing experience.

### Initial Configuration

In [main.tex](https://github.com/mjpc13/latex-dissertation-template/blob/main/main.tex) you need to change the following configurations:
- From line 158 to 162 you can insert your name, dissertation's name, place, supervisor and co-supervisor's name.
- In lines 211 and 212 you can change your epigraph (cool sentence to say)

In [title_page.tex](https://github.com/mjpc13/latex-dissertation-template/blob/main/title_page.tex) you need to change the following configurations:
- From line 16 to 18 change the Juries' names
- In line 28 change the sentence to match your course

To get your cover edit the [misc/Capa_Dissertacao_A4comPag.docx](https://github.com/mjpc13/latex-dissertation-template/blob/main/misc/Capa_Dissertacao_A4comPag.docx) and export **as PDF** with the name **cover.pdf** to the *images/* folder (replacing the default cover.pdf).

## Template Structure

The structure of this template is organized in the following fashion:

- `chapter/` hold the *.tex* files regarding your chapters (eg. Introduction, Background, Conclusion etc...)
- `bibliography/` have the `.bib` files
- `images/` is a directory intended to store your images
- `misc/` is a directory intended to store your other files. Can be used for store diagrams, ppts, etc...
- `appendix/` stores the files regarding your appendix

This is as simple as one can get. 

The [main.tex](https://github.com/mjpc13/latex-dissertation-template/blob/main/main.tex) is used to:
- Hold all the configurations (Formatting options, styling options etc...)
- Hold the information regarding your dissertation (Title, your name, supervisor etc...)
- Import the Chapter files (you have to import the chapters into the `main.tex` for them to compile)
- Import references and appendix

The [list_acronyms.tex](https://github.com/mjpc13/latex-dissertation-template/blob/main/list_acronyms.tex) is used to:
- Hold all your acronyms (that can be referenced with `\acs{}` for short and `\acl{}` for the long form)
