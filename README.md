Govstaffquestionnaire
Paper questionnaire for UK school governors to use with school staff.
This questionnaire has been built in LaTeX. For more on how to install and use LaTeX visit http://www.latex-project.org/ Unlike a questionnaire produced in word processing software the programming controls the whole layout of the questionnaire. 


Notes on use. 
    
The file paperandpencil.sty needs to place in the same directory as the .tex file. I had trouble finding it, but found the code elshwere on Github. I pasted this into a text editor, saved it as paperandpencil.sty, and put it in the same directory as the .tex file.
    
    
    The document class needs to be {scrreprt}. This is in the first page documentation, but I managed to miss it.
    To set page numbers \pagestyle{plain} is required and the \pagenumbering and \setcounter options need to be set.
