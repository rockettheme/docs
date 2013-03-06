RocketTheme Documentation
=========================
This repository contains the source of the RocketTheme documentation, currently accessible at [http://rockettheme.com/docs]().

The documentation is contained in [Docs/](Docs) and is structured in folders, exactly as you see them on the main website.

You can read all of the documentation within as its just in plain text files, marked up with [Markdown](http://daringfireball.net/projects/markdown/).

If you would like a local copy of the documentation, you can either [download it](https://github.com/rockettheme/docs/archive/master.zip) or you can clone the reopistory by running the follwing command:

~~~
git clone git://github.com/rockettheme/docs rockettheme-docs
~~~


Contributing
------------
Contributing to the documentation is very simple. Feel free to fork the repository, add your changes and give back by issuing a pull request. You can even edit the docs directly on GitHub, without having to ever download the files. Make sure to follow the conventions before issuing a pull request.

You are also very welcome to make any suggestions or report any kind of problem with the documentation by opening a new [Issue](https://github.com/rockettheme/docs/issues/new).

If you decide to fork for providing new content as commits. Please ensure you create a branch for your changes, before making them. This will make the process of integrating them more easier. Every change must pass through the `staging` branch first, so please ensure your pull-requests are directed to the proper branch.

To get started with a local environment into the proper `staging` branch, you can run these commands:

~~~
git clone git://github.com/rockettheme/docs rockettheme-docs
cd rockettheme-docs
git checkout -b staging origin/staging
~~~


Conventions
-----------
This is a list of few conventions we follow when writing documentation that help keep the repository well organized and consistent. Feel free to use any other file in the docs as reference. We also have a [skeleton](Skeleton.md) with all the conventions in place and with many examples of Markdown in use.

* Every change/pull request must be applied or requested to the [staging branch](https://github.com/rockettheme/docs/tree/staging). Once reviewed, approved and pulled, it will get merged into the **master** branch and automatically picked up by the website.

* Folder and file names must be written in snake_case. For example, if you wanted to convert “How to Install” in snake_case, you would name it “how_to_install”.

* There are some reserved names that can’t be used for anything but the scope they are intended for:
    * **README.md**: [ _file_ ] This is a reserved name of GitHub, used to describe the content of a particular repository directory, like this you are reading right now.

    * **TOC.md**: [ _file_ ] TOC (Table Of Content) does represent the structure of a project. Its content is a list of links to the various documents in the project. The TOC is represented as sidebars in the [RocketTheme Docs](http://rockettheme.com/docs).

    * **INDEX.md**: [ _file_ ] This file defines the default content for a folder. Exatly like HTML pages, if you hit a folder without specifying any file, INDEX.md (if found) will be assumed.

    * **REDIRECT.md**: [ _file_ ] This file sorely purpose is to redirect projects to different locations. For example, if a project `/docs/project/subproject/` contains a `REDIRECT.md`, when hitting on the web the `subproject` page, you’ll get redirect to `project`. By default it takes you back one level, although you can configure where to redirect to through YAML headers ([read more about YAML headers below](#yaml-headers)).

    * **assets**: [ _folder_ ] When the project requires assets, such as images, they can be placed in the `assets` folder. Any filename inside `assets` must follow the same rules as any other file name (snake_case, no reserved names, etc).

* Every header, except for the title one, must be preceeded by 2 empty lines and succeeded by no empty line.

* Headers sub lines (`=` and `-`) must always align to the header text. Because this can easily get confusing, be sure to use a mono-spaced fonts. Here a couple of examples of well aligned headers:

    ~~~
    Header H1
    =========

    Header H2
    ---------
    ~~~


YAML Headers
------------
Our Markdown implementation uses special [YAML headers](http://www.yaml.org/spec/1.2/spec.html). These headers are encapsuled in between a set of three dashes and an empty line. This is how a YAML header looks like:

~~~ .yaml
---
title: Project Title
parent: ../../
parent_title: Return to the Generic Projects
---
~~~

The headers allow for a much flexible output. For example we can define a title of a Markdown file based on its header title variable, rather than the file name itself.

Below is a list of supported YAML variables that can be used and a description on what they do:

* **title**: The title of the article. This is used whenever a page needs to be referenced.

    ~~~
    ---
    title: Hello World!
    ---
    ~~~

* **parent**: _(defaults: ../)_ This is the reference for the back link to point to.

    ~~~
    ---
    parent: ../extensions/
    ---
    ~~~

* **parent_title**: _(defaults: Return to the previous Documentation)_ The text to be associated to the `parent`.

    ~~~
    ---
    parent_title: Back to Extensions!
    ---
    ~~~

If you have any question feel free to open an [Issue](https://github.com/rockettheme/docs/issues/new).

_The RocketTheme Team_
