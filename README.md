RocketTheme Documentation
========================

This repository contains the source of the RocketTheme documentation, currently accessible at [http://rockettheme.com/docs]().

The documentation is contained in [Docs/](Docs/) and is structured in folders, exactly as you see them on the main website.

You can read all of the documentation within as its just in plain text files, marked up with [Markdown](http://daringfireball.net/projects/markdown/).

If you would like a local copy of the documentation, you can either [download it](https://github.com/rockettheme/docs/archive/master.zip) or you can clone the reopistory by running the follwing command:

	git clone git://github.com/rockettheme/docs rockettheme-docs
	
Contributing
-----------------

Contributing to the documentation is very simple. Feel free to fork the repository, add your changes and give back by issuing a pull request. You can even edit the docs directly on github, without having to ever download the files. Make sure to follow the conventions before issuing a pull request. 

You are also very welcome to make any suggestions or report any kind of problem with the documentation by opening a new [Issue](https://github.com/rockettheme/docs/issues/new).

If you decide to fork for providing new content as commits. Please ensure you create a branch for your changes, before making them. This will make the process of integrating them more easier.

Conventions
-----------------

This is a list of few conventions we follow when writing documentation that help keep the repository well organized and consistent. Feel free to use any other file in the docs as reference. We also have a [skelethon](Skelethon.md) with all the conventions in place and with many examples of Markdown in use.

* Every change/pull request must be applied or requested to the [dev branch](https://github.com/rockettheme/docs/tree/dev). Once reviewed, approved and pulled, it will get merged into the **master** branch and automatically picked up by the website.

* Folder and file names must be written in snake_case. For example if you wanted to convert “How to Install” in snake_case, you would name it “how_to_install”.

* There are reserved names that can’t be used for anything but the scope they are intended for:
	* `README.md`: This is a reserved name of GitHub, used to describe the content of a particular repository directory, like this you are reading right now.
	* `TOC.md`: TOC (Table Of Content) does usually resides alone at the top level of a directory. Its content is a list of links to the subfolders. This is represented as sidebars in the [RocketTheme Docs](http://rockettheme.com/docs).
	* `INDEX.md`: This file defines the default content for a folder. Exatly like HTML pages, if you hit a folder without specifying any file, INDEX.md (if found) will be assumed.
	
	
_The RocketTheme Team_
