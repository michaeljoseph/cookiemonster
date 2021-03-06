section: intro
background-image: url(resources/sesame-street-cookie-monster-wallpapers_35947_1680x1050.jpg)
class: inverse, bottom

# how
# me became
# cookiemonster

http://michaeljoseph.github.io/cookiemonster
???
**0.0.1**

Hi, My name is Michael.

And I'm a cookiemonster.

Cos me love cookies.

Ground rules:

- me love heckers
- questions and interjections and interruptions are encouraged

---
background-image: url(resources/google-cookie_00405143.jpg)
class: center

## User to Complainer to Helper to Core

???
**0.0.2**

My journey through the roles of the cookiecutter Open Source Project

---
background-image: url(resources/puppet-blue-awesome.jpg)
class: inverse, center, middle

## an evolution of contributing
## to the development
## of an
## open source software development

???
**0.0.3**
---
class: inverse
background-image:url(resources/mj.png)
# me talk about me

???
**0.1**

I'm, I guess what you'd call a backend developer.

I self-identify as a Python developer, but I've written production code in
a lot of languages. Python is just the best :heart:

---
class: center, inverse
# polyglot

## VB
--

## Java
--

## PHP
--

## C Sharp (thanks Markdown)
???
I've been writing production code since the turn of the century.
Which, I guess makes me a greybeard. Even though I only have
one in my moustache right now.

And I've seen (and been part of) waxing and waning trends.

Obviously not that kind of waxing...

Perhaps not as obvious, is that my beard is an intentional
part of this act...
You're welcome guys.
Also, the store was out of blue dye, so...
---
class: center, inverse
# polyglot

## Python
--

## Ruby (shush)

???
**0.2**

The more language you see, the less appetite you have for religious wars.

`DevError`: Only using tools written in languages that you like is not necessary.

Sometimes you can just be the user of a piece of software. Programmers make _the_ _worst_ users.

Don't judge a language by the first time you tried and didn't
like it.

PHP / Java / Perl / `your_favourite_whipping_language` implementations are running the Internet as we (I) speak.

---
class: inverse, center, middle
# me live in terminal
## so...
---
class: center, middle
# me ![heart](resources/heart.png) CLIs
## because
# me ![heart](resources/heart.png) automation
???
**0.3.0**

Peter's opening talk: automation increases your change-making confidence 

Many times, as I'm in the middle of telling someone about this amazing new CLI tool I've discovered and starred, like...

---
background-image: url(resources/butterfly.gif)
???
**0.3.1**

butterfly web term, so you never have to leave your browser

---
background-image: url(resources/rainbowstream.gif)
???
**0.3.2**

rainbowstream, a twitter client

it displays images in the terminal!!

---
background-image: url(resources/jrnl.png)
???
**0.3.3**

jrnl- a note taker that uses a simple entry timestamped text file, supports tags and JSON exports.

---
background-image: url(resources/youtube-dl.png)
background-size: 100%
???
**0.3.4**

YouTube Downloader

And then they ask me what language it's written in and wrinkle their noses
in faint disgust at the horror of running a program in an unattractive language.

---
class: inverse, center
# lightning talk ?
## How me Learned To Stop Worrying And Love The CLI
???
**0.3.5**

Good CLIs slip down into the fabric of the interface.

Does anyone care what language diff or ack are written in, as long as they work?

I'm going to resist the urge to spin this off into a lightning talk.

---
section: cookiecutter
class: bottom, center
background-image: url(resources/cookiecutter.png)

## https://github.com/audreyr/cookiecutter

???
**1.0**

Ok, 17 slides in, let's start this talk!

Cookiecutter is a CLI tool that lets you template your projects.

- project generation tool

- creates the files and directories setup just right to start a new project.

- Jinja templated so that you can customise the template.

- the CLI processes a template repo and prompts you for values to replace placeholder text

---
background-image: url(resources/stars.png)

![cookiecutter](resources/cookiecutter.png)
???
**1.1**

At 1000 stars, cookiecutter is medium sized.

`changes` (a tool I write to automate releasing python libraries) is, by comparison, an infant, at 50 stars. More about `changes` later.

It's sorta like a teenaged open source project (compared to the 10k stars luminaries like httpie, django and requests)

---
background-image: url(resources/sloccount.png)
???
Limiting scope is a feature, so the codebase is relatively small  
---
background-image: url(resources/appveyor.png)

???
Inclusive: Python 3 and Windows
---
class: center
# why me ![heart](resources/heart.png) cookiecutter as a programming user

## Starting a new project should be as easy as

```bash
git checkout -b new-feature
```

???
**1.2**

As a programming user, I create new projects.

I cringed everytime I `cp -R ../` from one of my example implementations

You want to be able to easily generate a new thing and feed improvements back into
the template.

As a member of the development team, I want there to be once place for me
to make improvements to the structure and conventions of our applications.

---
class: center, inverse
# why me ![heart](resources/heart.png) hacking on cookiecutter

## Python (obvs)

???
**1.3**

It's written in Python

It's made up of the bread and butter backend programming of my youth.
--

## Command line I/O

---
class: center, inverse
# why me ![heart](resources/heart.png) cookiecutter as a developer

## well documented (http://cookiecutter.rtfd.org)
---
background-image: url(resources/docs.gif)
background-size: 100%
---
class: bottom, inverse
background-image: url(resources/coveralls.png)
# we gots you covered
???
Well tested
---
background-image: url(resources/tested.png)

???
2 : 1 ratio of test to application code
---
# why me ![heart](resources/heart.png) cookiecutter as a programmer

## enthusiastic and inclusive community
---
background-image:url(resources/issues.png)
---
background-image:url(resources/pulls.png)
---
background-image:url(resources/milestones.png)
---
class: inverse, center
# Philosophy
--

## The Unix Way
## Doing One Thing Well
--

## Onion Programming
## Adding One More Layer Of Abstraction
---

class: inverse
background-image:url(resources/itch.jpg)
# why me ![heart](resources/heart.png) cookiecutter as a programmer

???
**1.4**

Scratches my itches

Segue into dayjob usecases

---
background-image: url(resources/microservices.png)

---
class: center
# use case: microservice architectures

## libraries, services, ui components

???
**1.5**

Useful at your dayjob.

The latest koolaid has you quickly reaching the point of repeating yourself very quickly,
and the faster and frictionlessly (aka smoothly) you can start a new project, or crank
out a release, the better.

---
class: inverse, center
# use case: web app installations

???
**1.6**

per-client instances of an application

allows codification of conventions

opportunity to feed back improvements to the template
---
class: inverse
background-image: url(resources/ccc.png)
# my cookiecutter template

???
Python packages, the way I like it.
---
class: inverse, middle, center
# cookiecutter demo
---
background-image: url(resources/cookiecutter-demo.gif)

???
So, that's cool, but not quite enough for me.

Because I can't automate it 
---
class: inverse, bottom, left
background-image:url(resources/itch.jpg)
# my itches 
???
Which makes me itchy.
---
background-image: url(resources/google-cookie_00405143.jpg)
class: center

## User to Complainer to Helper to Core

???
**2.0**
So, that's how I got into cookiecutter

This part of the story chronicles my personal journey
from an outsider, to a member of the cookiecutter community
---
class: middle, right
background-image: url(resources/changes.png)
# origin story
???
**2.1**

Origin Story or the itch I wanted to scratch.

I built changes so I could stop repeating myself
everytime I wanted to cut a new release of a python
package.
---
class: inverse, middle, center
# changes demo
---
background-image: url(resources/changes-demo.gif)
---
class: top, center, inverse
background-image: url(resources/changes-start.png)
# changes::start

???
**2.3**

Like all good things, changes::start started life
as a small shell script.
---
background-image: url(resources/small-shell-script.jpg)

???
Turns out, that this wasn't an empty threat.

You may be aware of this phenomenon under it's hashtagged name:
devops.

Sorry, DBAs.

---
class: inverse
background-image: url(resources/cookiecutter.main.cookiecutter.png)
# from cookiecutter.main import cookiecutter

???
**2.2**

In order to `start`, I _need_ to programatically generate a cookiecutter template (optimised for changes opinions about python packages).

> I have a dream, where the distance from thought to indexable
> resource, is only a naturally crafter cli command away

---
class: top, center, inverse
background-image: url(resources/changes-flow.png)
# changes:flow

???
**2.4**

Think `git-flow` for library release management and development
Upload feature branches as intermediate library versions.

---
class: inverse, middle, center
background-image: url(resources/puppet-blue-awesome.jpg)
# back to the story
???
**2.5**

First I search the issues, like a good person

Found many attempts, nothing merged

---
background-image: url(resources/triage.jpg)

???
**2.6**

Triage
---
class: right
background-image: url(resources/review.jpg)
# Review

???
**2.7**

***Git diff advertising company; adverts on diff views***

Similar features, code reviews

Review and encourage

---
class: center
# Code
## small changeset, many pulls
???
**2.8**

---
class: center
# AUTHORS.md

```python
assert '@michaeljoseph' in open(AUTHORS.md).read()
```

???
**2.9**

My bugs are on your computer....

---
background-image: url(resources/core.png)
???
**2.10**

Largely on the back of extra context triage, I get the bit.
Now to wield it with great responsibility.

---
section: extra context
class: center
# extra context overview

???
**3.0**

So, let's take quick walk through the actual feature
and the story of it's development and review.
---
class: center
# API + CLI (context overrides)
---
class: center
# cookiecutter.json (template defaults)
---
class: center
# user context (~/.cookiecutterrc)
---
class: inverse, center
# we need **project context** (overrides)

---
class: center
# extra context PR tour
https://github.com/audreyr/cookiecutter/pull/260

???
**3.2**

Splat+}

---
class: inverse, center
# lessons

## don't get carried away
--

## small changes are gentler on reviewers (open source context is expensive)
---
class: center
# lessons
## documentation is a first class citizen
--

## keep focused
---
class: center
# result
## compromise, pragmatism and followup

cherry picking is as fun and easy as it sounds

???
**3.4**

---
section: outro
class: inverse, center
# summary
## use cookiecutter, because everyone loves cookies
---
class: inverse, center
# summary
## be open source
---
class: inverse, center
# summary
## automate
---
class: top, center
# AMA
![ama](resources/ama-cookiemonster.gif)
---
class: inverse, top, center
# AMA
![ama](resources/eatcookie.gif)
---
class: inverse
background-image: url(resources/cookie-monster-28559-1440x900.jpg)

# me out
