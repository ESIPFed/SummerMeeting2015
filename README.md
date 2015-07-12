ESIP Summer Meeting
=======

This is the collaborative space for the upcoming [ESIP Summer Meeting](http://esipfed.github.io/). Please organize your projects into folders and include all appropriate and necessary libraries. Please include a README.md, installation instructions or setup files, and full documentation in any submitted folders. Please update this readme with your package name in the 


* [Other Online Collaboration spaces](#collaboration-spaces)
* [Social Media](#twitter)
* [Submitting Pull Requests](#pull-requests)
* [Using Git Natively](#native)
* [Writing in Markdown](#markdown)
* [Submitted Packages](#packages)
* [Contributors](#cont)


Other ESIP Collaboration Spaces<a id="collaboration-spaces"></a>
---
* [ESIP Commons](http://commons.esipfed.org/)
* [ESIP Wiki](http://wiki.esipfed.org/index.php/Main_Page)

Tweeting and Social Media<a id="twitter"></a>
---
If you are considering tweeting about the site, please use the hashtag [#ESIPfed](https://twitter.com/search?q=%23esipfed&src=typd)

Submitting a Pull Request to the Website<a id="pull-requests"></a>
---
```
0. Download and install hub.github.com 
1. File JIRA issue for your update at https://github.com/ESIPFed/SummerMeeting2015/issues
- you will get issue id e.g., #X where X is the issue ID, e.g., if X is 101, then #101
2. git clone https://github.com/ESIPFed/SummerMeeting2015.git
3. cd SummerMeeting2015
4. git checkout -b PR-X
5. edit files to commit
6. git status (make sure it shows what files you expected to edit)
7. git add <files>
8. git commit -m “fix for #X contributed by <your username>”
9. git fork
10. git push -u <your git username> PR-X
11. git pull-request
```

Using git natively<a id="native"></a>
--------

On Linux and more recent Mac OS, "git" is a native command-line tool. Check to see if you have git by typing "git status" at any command line prompt. If you do not get some sort of response indicating an error to find git, it may already be installed. If not, on most Linux distributions you can use apt-get (with or without sudo depending on permissions) or yum to install git. If not, on Mac OS, you can (and should) use brew to install git. If you do not have brew on Mac OS, please install brew by visiting the brew site [HomeBrew](http://brew.sh/). Brew is the ideal package manager for Mac OS. Note that you may need to install a few additional libraries, but the site will help. 


Writing updates in Markdown<a id="markdown"></a>
-------------

When writing to the README and other markdown files, please use markdown syntax. A good overview is found at [Assemble](http://assemble.io/docs/Cheatsheet-Markdown.html). GitHub-flavored markdown is slightly different; a good overview is found here [Official GitHub MarkDown Help](https://help.github.com/articles/github-flavored-markdown/) and a general overview of how git syntax can be used effectively is here [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.md).

Packages Submitted<a id="packages"></a>
------

Please write package submissions as bullets with internal links by adding to the README.md like this:

        * [Package Name](link to repository)

Contributors and Authors<a id="cont"></a>
-------

* Annie Burgess
* Fox Peterson

License
------
Please read the license file regarding use of projects in this repository. 
