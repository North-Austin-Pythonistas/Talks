
Thank you to everyone who attended Saturday's talk!

First, next meeting has not been scheduled yet but I expect it will be
the third weekend of January at the earliest. The venue continues to
be the Pflugerville Public library.

It's my belief that we write computer programs for people. As a
programmer, I investigate any technique or technology that can improve
the experience of the person who has to interact with my code in the
future. I joke that I imagine that person is an axe murder with my
home address, but more often that faceless future programmer is me. My
wife taught me about being kind to my future self, so that often
informs my decisions about how much effort to invest in code.

Given that, the topic for the meeting was Python 3 type hinting; what
they are, what their benefits are and how to add them to your
code. The take aways are:

- Type hints communicate the developers intent
- Type hints are ignored by the Python compiler
- Type hints are used by third party code checkers like "mypy"
- Type hints can be applied incremently to code

There was a lot of discussion about pros and cons of add type hinting
to your code. The pros seem to revolve around code that is intended to
be consumed by other programmers or loose teams that may not operate
with the same constraints when it comes to development. The cons were
increased code complexity and the perception that Python's clean
dynamic nature is beginning to look more like statically typed C++.

Perhaps the best result of type hinting we identified is code
completion in integrated development editors, which for many was worth
the price of admission.

I touched briefly on automating the use of mypy (and other code
checkers) using the pre-commit package. If you work on a team, having
your team use and pass pre-commit tests in the local repos is a great
way improve the quality of pull requests that reach the origin
repository. If you don't work in a team, using pre-commit is still a
great way to automate running code checkers to up your game.

There was also a short discussion about the amount of time we invest
to realize small gains in performance and of course there is a
relevant [XKCD strip for that][0]

Happy holidays everyone and I look forward to what we're going to
learn together in 2020!

Send me your topic suggestions and I'll see you next month!

Erik


Introduction to Type Hinting with Python 3 - URLS:

* [https://docs.python.org/3.7/library/typing.html][1]
* [https://mypy.readthedocs.io/en/latest][2]
* [https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html][3]
* [https://realpython.com/python-type-checking/][4]
* [https://pre-commit.com][5]
* [https://black.readthedocs.io/en/stable/][6]
* [https://github.com/North-Austin-Pythonistas/Talks][7]


Other Topics Discussed:

- Programming + Subject matter experience == Super Power
- Parametrizing unit tests with pytest to increase code coverage without writing 1:1 tests
- Python virtual environments are good
- [Why You Should Use "python -m pip"][8]
- [Thinking in Python][9]


PyPI Modules Worth Mentioning:

- [click][10] - create beautiful command line interfaces
- [colorama][11] - terminal text color module
- [keyring][12] - provides easy acces to system keyring services
- [tqdm][13] - fast, extensible progress bar for loops and CLI

Builtin Modules Worth Metioning:

- [argparse][14] - create ugly functional command line interfaces
- [venv][15] - module to create and manage virtual environments
- [zipfile][16] - create and manipulate Zip archive files


[0]: https://xkcd.com/1319/
[1]: https://docs.python.org/3.7/library/typing.html
[2]: https://mypy.readthedocs.io/en/latest
[3]: https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html
[4]: https://realpython.com/python-type-checking/
[5]: https://pre-commit.com
[6]: https://black.readthedocs.io/en/stable/
[7]: https://github.com/North-Austin-Pythonistas/Talks
[8]: https://snarky.ca/why-you-should-use-python-m-pip/
[9]: https://blog.dropbox.com/topics/work-culture/-the-mind-at-work--guido-van-rossum-on-how-python-makes-thinking
[10]: https://palletsprojects.com/p/click/
[11]: https://github.com/tartley/colorama
[12]: https://github.com/jaraco/keyring
[13]: https://github.com/tqdm/tqdm
[14]: https://docs.python.org/3.7/library/argparse.html
[15]: https://docs.python.org/3.7/library/venv.html
[16]: https://docs.python.org/3.7/library/zipfile.html
