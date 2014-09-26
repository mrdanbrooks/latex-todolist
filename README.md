latex-todolist
==============

This style file provides a TODO list macro for your latex documents!
It creates highly visible notes that appear in the rendered document for things needing to be done in your document. 
Additionally, an optional extra page with a list of all your todo notes can be added to the end of your document.
The notes can all be easily hidden using a single command.

Example Usage
-------------
Simply download ``todolist.sty`` and include it in your source directory, along with your tex files, and use it like such.

```
\documentclass{article}
\usepackage{todolist}

% Example Usage
\begin{document}

% Uncomment the following line to hide all todo notes.
%\hidetodo

\noindent
hi there \\
\todo{this thing} Inside these words is\todo{do me}a todo.

% Comment the following lines to hide the todolist at the end of the document
\newpage
\listtodos

\end{document}
```
