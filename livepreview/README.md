## livepreview

A simple .bashrc alias for directly compiling of your *.tex file with *.pdf autoupdate functionality, each time when you save your *.tex file.

*Install*  
You need to have installed *texlive* on your linux machine. Furthermore, you need *latexmk* which should be come auto-installed together with *texlive*

*Setup*  
Copy the alias in .bashrc in your personal bash config (~/.bashrc)

*Usage*  
Run the following in your current work directory

~~~
$ livepreview
~~~

If you have more than one *.tex file in your work directory, run

~~~
$ livepreview yourmainfile.tex
~~~

It works well for paper like documnts. If you want to write a thesis or book, I recommend to use a makefile instead, because of compiling time.
