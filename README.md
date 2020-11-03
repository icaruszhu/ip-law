---
Title: YALA's Version-Controlled Intellectual Property Law Study Guide for BLS Students
Author: Chen Zhu
---

# Intellectual Property Law: Contexts, Doctrines and Debates

*A Version-Controlled IP Course Guide for Final-Year Undergraduate Law Students at Birmingham Law School* 

This course guide is designed by Chen Zhu a.k.a [YALA, Yet Another Legal Academic] (https://icaruszhu.github.io/), who has been teaching IP law at Birmingham Law School since 2014.

I am grateful to our students who have taken this IP course in the past years. Your participation and feedback have helped to make this course grow and mature.


# Background
The text of this guide is stored and distributed in the non-proprietary plain text formats including ```markdown``` and ```Emacs's org-mode```. It is licensed under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) with ```org```/```markdown``` source code available. My aim is to use free and open source software (FOSS) to generate all course contents, which need to be shareable, sustainable, and remixable. My main text editor for writing course materials is [GNU/Emacs](https://www.gnu.org/software/emacs/), which is used to edit both [Org](https://orgmode.org/) and Markdown (thanks to the [markdown-mode](https://jblevins.org/projects/markdown-mode/)) files. I also use [Zettlr](https://www.zettlr.com/)  as a secondary markdown editor. Zettlr is a fantastic FOSS tool that brilliantly  implements the German sociologist Niklas Luhmann's Zettelkasten method, and I like its versatility and elegance. 

The course guide is developed over a period of time and its textual format has is version controlled by Git. This means that the guide is a work in constant and possibly perpetual progress. 

## Dedication
This course guide is dedicated to my father Jianzhong Zhu (1951-2020), who sadly passed away in October 2020 (after losing a long battle against a host of painful illnesses). 

# "Intellectuality" in "Intellectual Property"
This module encourages students to be attentive to dynamic *intellectual* processes behind those creative activities regulated or unregulated by IP law. A study of *Intellectual* Property without knowing relevant *intellectual* processes is like ordering a cup of [latte](https://en.wikipedia.org/wiki/Latte) without having milk. [^1]

# Object-oriented approach: A material history of IP  
This IP course adopts an "object"-oriented approach. I have gradually built a curated collection of  "objects" and "artifacts" to show IP law's relevance in everyday life.[^2] This approach is informed by the "new materialist" theory that is gradually gaining momentum in critical legal scholarship. 


# Intellectual "Un-property"
This course also challenges students to view so-called "intellectual property" in its negative space. The proprietary scope of IP is not unlimited, but it is, and should be, carefully defined and confined. A quick Google N-gram query  allows us to do a rudimentary Foucauldian genealogical search of the term "intellectual property", whose rise is found to be a fairly recent phenomenon. By quickly eyeballing the graph, it is not difficult to see that the term is not widely used before 1970s.

![IP trend](https://raw.githubusercontent.com/icaruszhu/commit/master/image/ngram-IP-trend.png)

The course tries to make students see the "negative space" of IP or what I call "Intellectual Un-property" (IuP), which should not be seen as the left-over part of the positive restriction imposed by IP as exclusive rights. Instead, IuP is an integral part of what IP is and its space needs to be carefully designed.


# Literate Programming and executable code blocks

For those who are curious:  The [Emacs's Org-mode](https://orgmode.org/) version of seminar sheets always contain a line  of```pandoc``` code that can be executed within a [Org-Babel](https://orgmode.org/worg/org-contrib/babel/) block. This code will export the current seminar sheet into PDF (or any other formats a you wish). The ```pandoc``` codeblock section is tagged with ```:noexport:```, which will prohibit  itself from being exported. The code can be executed by typing =Ctrl-c= twice. It looks like this:  

```Org-mode
#+BEGIN_SRC sh
pandoc seminar1*.org -o ~/Desktop/seminar1.pdf --pdf-engine=xelatex
#+END_SRC
```

The above code will send a decently formatted PDF file to your ```~/Desktop```. 

# Download and Fork the Course 
## Download
- You can download the repo using the Github GUI.
- Alternatively, you can use the command line. Type this command in your terminal:  ```git clone https://github.com/icaruszhu/commit.git```

## Fork 

Please feel free to fork this course guide repo. Pull requests are also welcome. 

# Footnotes


[^1]: You may try this to a ~~barrister~~ barista at a Starbucks shop: "Could I have a tall cup of latte? No milk please!" See what reaction you will get. Studying IP without knowing the "intellectual" background  is like having latte without milk.  

[^2]: I am inspired by Dan Hunter and Claudy Kamp, *A History of Intellectual Property in 50 Objects* (Cambridge University Press 2019)
