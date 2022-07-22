# Latex Dissertation Template

This is a public latex template repository to write dissertations. It complies with the [visual identity of Coimbra University](https://www.uc.pt/identidadevisual). It was designed for the Faculdade de Ciências e Tecnologias da Universidade de Coimbra, but it can be adapted. In you check the generated sample PDF in the [github pages](https://mjpc13.github.io/latex-dissertation-template/) of this repository.

# Getting Started

This is a very quick overview to get you started. You will be able to find the full documentation in the docs tab in a near future.

#### Github

This is the prefered method to work with this template. For this you require to have LaTeX installed in your computer and some sort of text editor, I advised using VSCode with the LaTeX extension. Learn more [here](https://guillaumeblanchet.medium.com/using-latex-in-visual-studio-code-on-windows-121032043dad).

#### Overleaf

There is no reason for this template not work directly in overleaf. Simply download the `.zip` file from this repository, extract it and import the folder over to Overleaf.


## Template Structure

The structure of this template is organized in the following fashion:

- `chapter/` hold the *.tex* files regarding your chapters (eg. Introduction, Background, Conclusion etc...)
- `bibliography/` have the `.bib` files
- `images/` is a directory intended to store your images
- `misc/` is a directory intended to store your other files. Can be used for store diagrams, ppt, etc...
- `appendix/` stores the files regarding your appendix

This is as simple as one can get. 

The `main.tex` is used to:
- Hold all the configurations (Formating options, styling options etc...)
- Hold the informations regarding your dissertation (Title, your name, supervisor etc...)
- Import the Chapter files (you have to import the chapters into the `main.tex` for them to compile)
- Import references and appendix
