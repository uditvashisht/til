# TIL

> Today I Learned

A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies. These are things that don't really
warrant a full blog post.


_2 TILs and counting..._

---

### Categories

* [Git](#git)
* [Python](#python)

---

### Git

- [Change the remote origin of an existing repository](git/change-remote-origin.md)

### Python

- [Use readline() to get header of the files](python/use-readline-to-get-header-of-files.md)

## Usage

After creating a new entry, run `./createReadme.py > README.md` to regenerate
the readme with the new data.

If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -




## About

I shamelessly stole the above idea from
[jima80525/til](https://github.com/jima80525/til) who claims to have stolen
it from others.

## Other TIL Collections

* [jima80525/til](https://github.com/jima80525/til)
* [Today I Learned by Hashrocket](https://til.hashrocket.com)
* [jwworth/til](https://github.com/jwworth/til)
* [thoughtbot/til](https://github.com/thoughtbot/til)

## License

&copy; 2017-2018 Udit Vashisht

This repository is licensed under the MIT license. See `LICENSE` for
details.