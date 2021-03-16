Hello and welcome to this blog. Edit the `index.md` file to change this content. All pages on the blog, including this one, use [Markdown](https://guides.github.com/features/mastering-markdown/). You can include images:

![Image of fast.ai logo](images/logo.png)

## This is a title

And you can include links, like this [link to fast.ai](https://www.fast.ai). Posts will appear after this file. 


## 03-15-2021 going through the first fast.ai course

Took a while to set up, but like with most things I've learned over the years is that I'll miss some basic concept in setup and then spend hours chasing my tail trying
to understand why it wont run.

A couple things that I had to figure out to set up the fastai course on windows and running jupyter notebooks in chrome:

1. Download CUDA and pytorch, you'll most likely need a fresh install so just go and download it.
2. You'll need to pip install graphviz and then actually go to the website and download the actual file, and another thing
    a. the author dude Jeremy or whatever posted a tweet with a function definining gv, that will probably also need to be defined in the jupyter notebooks.
       otherwise you wont have any pretty pictures. (ill verify this with next lessons)
    b. i'll be storing the "dirty" files in a dirty folder and I'll pull the "clean" lessons out and place them in that folder. ill most likely do that after the intro.
3. Oh and the metrics that should display after training a program dont show up in visual code, and then checking if its a cat also doesn't work. Most likely we'll stick to 
   jupyter notebooks in Chrome. And since we found dark mode its not even that bad...
   speaking of which does git hub have dark mode?
