# how i became a cookiemonster
### the evolution of open source software development community contribution
http://michaeljoseph.github.io/cookiemonster
@michaeljoseph
![cookiemonster](resources/cookiemonster.gif)
???
0.0
This talk is about 3 things:

- cookiecutter

- open source and other distributed software development methodologies

- engaging with a technical community
---
class: center, inverse
title: about-me
# about me
![profile](resources/mj.png)
![profile](resources/juggler.jpeg)
???
0.1
I have, as usual, prepared this talk on very short notice
So, be prepared for my slides to be unpolished.
I shall attempt to make up for it with the words and exaggerated body language

I'm, I guess what you'd call a backend developer.

I self-identify as a Python developer, but I've written production code in
a lot of languages. Python is just the best :heart:
---
class: center, inverse
# polyglot
- VB
- Java
- PHP
- C#
- Python
- Ruby
???
0.2
The more language you see, the less appetite you have for religious wars.
DevError: Only using tools written in languages that you like is not necessary.
Sometimes you can just be the user of a piece of software. Programmers make
---
# better living through CLIs
???
0.3
Many times I'm telling someone about this amazing new cli tool I discovered...
---
![butterfly](resources/butterfly.png)
???
0.3.1
butterfly web term, so you never have to leave your browser
---
![rainbow](resources/rainbow.png)
???
0.3.2
rainbow, a twitter client
---
![fbcmd](resources/fbcmd.png)
???
0.3.3
fbcmd (written in PHP, spoiler alert)
---
![jrnl](resources/jrnl.png)
???
0.4
jrnl- a note taker.
And then they ask me what language it's written in and wrinkle their noses
in faint disgust at the horror of running a program in an unattractive language.
---
# lightning talk
## How I Learned To Stop Worrying And Love The CLI
???
0.5
Good CLIs slip down into the fabric of the interface.
Does anyone care what language diff or ack are written in, as long as they work?
I'm going to resist the urge to spin this off into a lightning talk
---
![logo](resources/cookiecutter.png)
## A command-line utility that creates projects from cookiecutters (project templates)
???
1.0
Ok, 10 slides in, let's start this talk!

Cookiecutter is a CLI that lets you template your projects.
- project generation tool
- creates the files and directories setup just right to start a new project.
- Jinja templated so that you can customise the template.
- the CLI processes a template repo and prompts you for value to search replace
---
# why: cookiecutter
???
1,1
If you're a programmer, you create new projects.
Everytime you done a cp -R and then some sed magic to spawn
a new instance from the last good instance you built a unix daemon gets his horns
---
# codifying conventions
???
1.2
You want to be able to easily generate a new thing and feed improvements back into
the template.
---
# use case: microservice archictures
- libraries
- services
- ui components
???
1.3
The latest koolaid has you quickly reaching the point of repeating yourself very quickly,
and the faster and frictionlessly (aka smoothly) you can start a new project, or crank
out a release, the better.
---
# use case: web app installations
???
1.4

---
# cookiecutter code
???
Stats, downloads, coverage
---
# cookiecutter community
???
Core
Developers
Users
---
# origin story
## changes::start
???
Origin Story or the itch I wanted to scratch.
---
# changes seque
???
In order to `start`, I _need_ to programatically generate a cookiecutter template (optimised for changes opinions about python packages).
---
![back](resources/meanwhile.gif)
???
back to the story
usage, issue search => triage
---
# Triage
???
Triage.
---
# Review
???
Git diff advertising company; comment advertising!!!
Similar features, code reviews
---
# Code
???
Small, focused pull requests
---
`python -c "print('@michaeljoseph' in open(AUTHORS.md).read())"`
???
My bugs are on your computer....
---
# commit bit
???
Largely on the back of extra context triage, I get the bit.
Now to wield it.
---
# extra context
???
---
# summary
---
align: center
# AMA
![ama-slideshow](ama-slideshow.gif)
???
Repeat the questions while you think of the answer.
---
# credits

http://cookiecutter.rtfd.org
https://github.com/audreyr/cookiecutter
http://michaeljoseph.github.io/cookiemonster
???
The End.
