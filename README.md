# Open Sorce Development Course at PyCon Israel 2023

* [site](https://osdc.code-maven.com/osdc-2023-07-pyconil/)

* Single-day event on: 2023.07.05

## Videos

No videos, this was a class-room worksop.


## My first contribution to an Open Source Python project

Writing Python inside a corporation is one thing, contributing to an open source project is a totally different experience. It brings a lot of joy.

During this workshop we'll go over the basics of contributing to an open source Python project hosted on GitHub and you will contribute to several open source projects.

* First we'll learn about forks and pull-requests on GitHub.
* Then GitHub Actions and Continuous Integration (CI) in general.
* Then we'll see the basics of writing tests and creating test coverage report.
* Finally we'll pick several Python projects, set up the local development environment for them and send at least one pull-request by each participant of the workshop.

You are expected to bring your own computer that already has Python installed and preferably also Docker, to make our tasks easier. You are expected to already have an account on GitHub and your picture or avatar added to it.


## Session:

* Self introduction
* [my open pull-requests](https://github.com/search?q=is%3Aopen%20is%3Apr%20author%3Aszabgab%20archived%3Afalse%20&type=pullrequests)
* Contributing to a complex project is, well, complex. We'll start small and hopefully by the end of the day you will have conbtributed to at least one project and you have the understanding of how to contribute to some other project

* What will we do today?
    * Pull-request to this project - a JSON file, CI, fixing
    * Introduction to Python testing.
    * Show GitHub Actions running Python tests.
    * Setting up local environment with or without Docker


* What stops you from contributing to an open source project?
* What is a contribution to an open source project?
    * Anwering a question on Stack Overflow
    * Opening and issue
    * Improving the documentation
    * Writing a test
    * Setting up Continuous Integration
    * Fixing a bug
    * Implementing a feature
* How to select an open source project to contribute to? [Which open source project to work on?](https://code-maven.com/slides/osdc/which-project)
    * A project you already use
    * GitHub Topic
        * [Explore](https://github.com/explore) - [Topics](https://github.com/topics)
        * [DL](https://github.com/topics/deep-learning) - [Deep Learning](https://github.com/topics/deep-learning)
        * [PyTorch](https://github.com/topics/pytorch)
    * Metrics:
        * Latest commit
        * Frequency of commit
        * Open issues
        * Open pull-requets
    * [PyDigger](https://pydigger.com/) - low hanging fruits
* Set up local development environment
    * [Flask](https://github.com/pallets/flask)
    * [PyDigger](https://github.com/szabgab/pydigger.com)
    * ...
    * [Development Containers](https://containers.dev/) - [devcontainers for VS Code](https://code.visualstudio.com/docs/devcontainers/containers)

## Communities

* [OSDC](https://osdc.code-maven.com/community) - [Zulip](https://osdc.zulipchat.com/)
* [Maakaf](https://github.com/maakaf)

## Assignments

* Send pull-request to our repository adding a json file to the `participants/` folder.
    * The filename is `your_github_user.json` in lower-case
    * It contains at least one field, `github` with your username again.

* Send a pull-request to the [List of all awesome lists](https://github.com/szabgab/awesome-lists).

* Setup PyDigger locally and run the tests.

* Find a project that does **not** have instructions how to set up the local development environment and run the tests. Set it up, send a PR explaining how to do that.

* Find a project that has tests, but no CI. Configure GitHub Actions.

* Find a project that does not have (enough) tests. Write a test.


## Notes

* [The 2022 December CI Challenge](https://code-maven.com/2022-december-ci-challenge)
* [Projects](https://osdc.code-maven.com/projects)
* [Bobby Tables](https://bobby-tables.com/)

