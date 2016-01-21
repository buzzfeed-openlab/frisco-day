# frisco-day

This repository automatically updates our site for Frisco Day.

If you have write access to it, you can add and edit text files to your heart's content. They'll be immediately visible at <http://callitfris.co>.

To add binary files (ie. images) you will have to clone the repository, add the image and push it. It sounds like a palaver, but if you use the [GitHub Desktop App](https://desktop.github.com/) it is pretty straightforward. 

Unfortunately, you can't use the Desktop App with 10.5 -- they require 10.9. So if you don't have 10.9, adding or swapping images is going to kind of suck. Sorry. There is a [nice list](http://git-scm.com/downloads/guis) of other GUI apps, or you can install [Homebrew]() and the use it to install git with `brew install git`

Then you can do the following in the terminal: `git clone git@github.com:buzzfeed-openlab/frisco-day.git` -- then you can drag your new photo into the `imgs` folder, and do `git add imgs/*` and then `git commit . -m "new photo"` and `git push`.

