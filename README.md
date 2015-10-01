# mead-compedium

A place to gather good meadmaking knowledge. Improvements are always welcome.
There is much experience out there that should be leveraged and shared.

If you just want the goodness, look at [MeadCompendium.pdf](https://github.com/kc0dhb/mead-compendium/raw/master/MeadCompendium.pdf)

# Contributing
This project is under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license. This basically means folks can use this information however they want as long as they give attribution. If they make changes they must release their changes as well under this same license. I learned this information basically for free, I'd like everyone else to be able to as well.

This project welcomes improvements in a variety of ways. Creating an issue is probably the easiest way to contribute.
An issue (for this project) could be a question, a request, a disagreement, a section of text you'd like to include,
or even as small as a grammar fix. When in doubt, file an issue.

Another way to contribute is with a Pull Request. Editing a file while logged in on github will automatically 
create a Pull Request. After the Pull Request has been added, there may be some discussion about it, and then
your goodness will be added. All contributors will be added to the 'Special Thanks' section unless otherwise requested.

Git can be confusing, so please don't let that get in the way; just file an issue or send an email and we'll get it worked out.

## Contribution caveats
There is a realization that LaTeX has somewhat of a learning curve, but it looks so nice! That is why knowledge in many forms is accepted and wanted! If latex feels like too much, just submit an issue with your text and I'll incorporate it.


# Building Locally
To build on your own machine you will need texlive and mhchem (texlive-science provides this in debian based distros).
On ubuntu/debian
```
sudo apt-get install texlive-science
```
And to build run
```
pdflatex -interaction=nonstopmode MeadCompendium.tex
```
from the root directory of the cloned project. For bibliography, index, glossary (yet to come), or section changes more than one run will have to be done.

